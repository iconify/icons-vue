<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fu_e-9zaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:screen-free-night" /></template>
<style>
.fu_e-9zaj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 11.073V6q0-.172.017-.343t.05-.34q.034-.168.084-.333t.115-.323t.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05Q8.328 2.5 8.5 2.5H12q.646 0 1.25.231m2.25 5.711v3.5M12.014 20.5H8.5q-.24 0-.477-.033q-.238-.032-.468-.097t-.451-.16t-.425-.221q-.204-.124-.39-.276q-.186-.151-.349-.327q-.164-.175-.302-.371t-.248-.409M16.5 3.5l-13 13m15.25-2.25a3.75 3.75 0 1 0 3 4.5a3 3 0 0 1-3-4.5");
}

</style>
