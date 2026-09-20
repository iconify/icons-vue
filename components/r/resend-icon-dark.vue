<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nm7lb_lvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:resend-icon-dark" /></template>
<style>
.nm7lb_lvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M156.575 0c49.582 0 79.07 29.488 79.07 68.632s-29.488 68.632-79.07 68.632h-25.052L256 256h-87.942l-94.729-90.03c-6.784-6.263-9.916-13.57-9.916-19.833c0-8.873 6.263-16.701 18.267-20.094l48.8-13.048c18.527-4.958 31.314-19.31 31.314-38.1c0-22.964-18.79-36.273-42.014-36.273H0V0z");
}

</style>
