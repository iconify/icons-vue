<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2-o8-omh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pentagon-dashed-duotone" /></template>
<style>
.a2-o8-omh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.9445 5.19963L12.6623 3.24463C12.2811 2.91813 11.7188 2.91813 11.3377 3.24463L9.05555 5.19963M5.63805 8.12723L3.35585 10.0822C3.04275 10.3503 2.92225 10.7808 3.05075 11.1725L3.84625 13.5981M5.24875 17.8739L6.04425 20.2995C6.18135 20.7176 6.57155 21.0003 7.01145 21.0003H9.74995M14.2499 21.0003H16.9886C17.4286 21.0003 17.8187 20.7176 17.9558 20.2995L18.7514 17.8739M20.1538 13.5981L20.9494 11.1725C21.0778 10.7808 20.9573 10.3503 20.6442 10.0822L18.362 8.12723");
}

</style>
