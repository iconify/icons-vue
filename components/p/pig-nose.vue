<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="x2lqr7v6y"/><ellipse class="blhrzuopu"/><ellipse class="yd1kpvyrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:pig-nose" /></template>
<style>
.blhrzuopu {
  cx: 10px;
  cy: 18px;
  fill: var(--svg-color--662113, #662113);
  rx: 4px;
  ry: 6px;
}

.x2lqr7v6y {
  fill: var(--svg-color--e6aaaa, #e6aaaa);
  d: path("M35 18c0 6.075-4.925 11-11 11H12C5.925 29 1 24.075 1 18S5.925 7 12 7h12c6.075 0 11 4.925 11 11");
}

.yd1kpvyrf {
  cx: 26px;
  cy: 18px;
  fill: var(--svg-color--662113, #662113);
  rx: 4px;
  ry: 6px;
}

</style>
