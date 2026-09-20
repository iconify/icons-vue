<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<circle class="efqo7obet"/><circle class="u3psqrlzl"/><path class="ptg-wob7r"/><path class="tw0mizbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:no-entry" /></template>
<style>
.efqo7obet {
  cx: 64px;
  cy: 64px;
  r: 60px;
  fill: var(--svg-color--c33, #c33);
}

.ptg-wob7r {
  fill: var(--svg-color--ff8a80, #ff8a80);
  d: path("M24.036 30.889C28.25 24.268 38.1 16.7 48.1 14.9c2.5-.4 5-.6 7.1.2c1.6.6 2.9 2.1 2 3.8c-.7 1.4-2.6 2-4.1 2.5c-9.38 3.1-18.323 10.592-22.071 15.21s-5.994 7.084-8.446 5.721c-2.27-.908-3.233-4.078 1.453-11.442");
}

.tw0mizbvb {
  fill: var(--svg-color--fff, #fff);
  d: path("M101.56 77.297H22.08a4.985 4.985 0 0 1-4.984-4.985V55.688a4.985 4.985 0 0 1 4.984-4.985h79.479a4.985 4.985 0 0 1 4.984 4.985v16.624a4.985 4.985 0 0 1-4.984 4.985");
}

.u3psqrlzl {
  cx: 60.1px;
  cy: 63.1px;
  r: 56.1px;
  fill: var(--svg-color--f44336, #f44336);
}

</style>
