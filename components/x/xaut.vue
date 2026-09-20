<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ww4fgz-rm"/><path clip-rule="evenodd" class="ud2auob3k"/><path class="ufoqkibbh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xaut" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ud2auob3k {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M17.631 3.9H6.343L3 11.238l9 8.862l9-8.862zM12.9 12.432c2.555-.107 4.502-.662 4.502-1.332c0-.745-2.418-1.35-5.4-1.35s-5.4.605-5.4 1.35c0 .67 1.945 1.224 4.498 1.331v4.07h1.8z");
}

.ufoqkibbh {
  fill: var(--svg-color--dda85b, #dda85b);
  d: path("M16.05 6.6h-8.1v1.8h3.15v3.15h1.8V8.4h3.15z");
}

.ww4fgz-rm {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 12c2.734 0 4.95-.403 4.95-.9s-2.216-.9-4.95-.9s-4.95.403-4.95.9s2.216.9 4.95.9");
}

</style>
