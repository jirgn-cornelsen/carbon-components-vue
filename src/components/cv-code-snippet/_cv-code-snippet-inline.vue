<template>
  <cv-feedback-button
    class="cv-code-snippet-inline"
    feedback="Copied!"
    inline
    aria-label="Copy code"
    @click="$emit('copy-code')"
  >
    <slot></slot>
  </cv-feedback-button>
</template>

<script>
import CvFeedbackButton from './_cv-feedback-button';

export default {
  name: 'CvCodeSnippetInline',
  components: {
    CvFeedbackButton,
  },
};
</script>
