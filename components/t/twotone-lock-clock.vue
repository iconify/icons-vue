<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e44s2acjp"/><path class="u1yaxccok"/><path class="aj67gvb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-lock-clock" /></template>
<style>
.aj67gvb6m {
  fill: currentColor;
  d: path("M18 13c-2.76 0-5 2.24-5 5s2.24 5 5 5s5-2.24 5-5s-2.24-5-5-5m1.65 7.35L17.5 18.2V15h1v2.79l1.85 1.85z");
}

.e44s2acjp {
  fill: currentColor;
  d: path("M11.29 20H6V10h12v1c.7 0 1.37.1 2 .29V10c0-1.1-.9-2-2-2h-1V6c0-2.76-2.24-5-5-5S7 3.24 7 6v2H6c-1.1 0-2 .9-2 2v10c0 1.1.9 2 2 2h6.26c-.42-.6-.75-1.28-.97-2M9 6c0-1.66 1.34-3 3-3s3 1.34 3 3v2H9z");
}

.u1yaxccok {
  fill: currentColor;
  d: path("M11 18c0-3.87 3.13-7 7-7v-1H6v10h5.29c-.19-.63-.29-1.3-.29-2");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
