<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="g5ua-304h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:top-arrow" /></template>
<style>
.g5ua-304h {
  fill: var(--svg-color--4d5357, #4d5357);
  d: path("M32 2L16 18h10v15h12V18h10zm0 60c-3.3 0-6-2.8-6-6.3v-9.3c0-3.5 2.7-6.3 6-6.3s6 2.8 6 6.3v9.3c0 3.5-2.7 6.3-6 6.3m0-18.6c-1.7 0-3 1.3-3 3v9.3c0 1.6 1.3 3 3 3s3-1.3 3-3v-9.3c0-1.7-1.3-3-3-3M22 40H10v3h4.5v19h3V43H22zm26 0h-6v22h3v-9.3h3c3.3 0 6-2.8 6-6.3c0-3.6-2.7-6.4-6-6.4m0 9.3h-3v-5.9h3c1.7 0 3 1.3 3 3s-1.3 2.9-3 2.9");
}

</style>
