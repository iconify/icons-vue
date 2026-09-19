<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4fxamulg"/><path class="hbgp0v76y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-tapas" /></template>
<style>
.b4fxamulg {
  fill: currentColor;
  d: path("M16 10V8h4v2c0 1.1-.9 2-2 2s-2-.9-2-2M4 6c-.28 0-.5-.22-.5-.5S3.72 5 4 5h6c.28 0 .5.22.5.5s-.22.5-.5.5zm6 6H4c-.28 0-.5-.22-.5-.5s.22-.5.5-.5h6c.28 0 .5.22.5.5s-.22.5-.5.5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.hbgp0v76y {
  fill: currentColor;
  d: path("M22 10V1h-8v9c0 1.86 1.28 3.41 3 3.86V21h-2v2h6v-2h-2v-7.14c1.72-.45 3-2 3-3.86m-2-7v3h-4V3zm-4 7V8h4v2c0 1.1-.9 2-2 2s-2-.9-2-2m-6-1H8V8h2a2.5 2.5 0 0 0 0-5H8V1H6v2H4a2.5 2.5 0 0 0 0 5h2v1H4a2.5 2.5 0 0 0 0 5h2v9h2v-9h2a2.5 2.5 0 0 0 0-5M4 6c-.28 0-.5-.22-.5-.5S3.72 5 4 5h6c.28 0 .5.22.5.5s-.22.5-.5.5zm6 6H4c-.28 0-.5-.22-.5-.5s.22-.5.5-.5h6c.28 0 .5.22.5.5s-.22.5-.5.5");
}

</style>
