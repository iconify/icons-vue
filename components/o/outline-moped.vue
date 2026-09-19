<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z54rniacm"/><path class="bdaznj-fp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-moped" /></template>
<style>
.bdaznj-fp {
  fill: currentColor;
  d: path("M5 6h5v2H5zm14 7c-1.66 0-3 1.34-3 3s1.34 3 3 3s3-1.34 3-3s-1.34-3-3-3m0 4c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1");
}

.z54rniacm {
  fill: currentColor;
  d: path("M19 7c0-1.1-.9-2-2-2h-3v2h3v2.65L13.52 14H10V9H6c-2.21 0-4 1.79-4 4v3h2c0 1.66 1.34 3 3 3s3-1.34 3-3h4.48L19 10.35zM4 14v-1c0-1.1.9-2 2-2h2v3zm3 3c-.55 0-1-.45-1-1h2c0 .55-.45 1-1 1");
}

</style>
