<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oaooigb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nos" /></template>
<style>
.oaooigb5t {
  fill: var(--svg-color--0de90b, #0de90b);
  d: path("M3 19.875h1.687V6.802c0-.663 1.047-1.333 1.755-.517l6.12 11.903h-2.25L7.22 12H5.25l3.937 7.875h6.2L8.09 5.576s-.72-1.44-2.43-1.44S3 5.88 3 6.403zm18-15.75h-1.688v13.09c0 .657-1.035 1.327-1.743.511L11.437 5.812h2.25L16.781 12h1.969l-3.926-7.875H8.625l7.296 14.31s.72 1.44 2.435 1.44S21 18.131 21 17.608z");
}

</style>
