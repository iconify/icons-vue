<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y81xvibdf"/><path class="xtll3pikn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-mode" /></template>
<style>
.xtll3pikn {
  fill: currentColor;
  d: path("M18.37 3.29c-.2-.2-.45-.29-.71-.29s-.51.1-.7.29l-1.83 1.83l3.75 3.75l1.83-1.83a.996.996 0 0 0 0-1.41zm-.56 6.65l-3.75-3.75L3 17.25V21h3.75zM5 19v-.92l9.06-9.06l.92.92L5.92 19z");
}

.y81xvibdf {
  fill: currentColor;
  d: path("M14.06 9.02L5 18.08V19h.92l9.06-9.06z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
