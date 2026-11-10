<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_4r1t8gj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:popcorn" /></template>
<style>
.u_4r1t8gj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 11C4.3705 10.53 4 9.79 4 9C4 7.62 5.1193 6.5 6.5 6.5C6.8626 6.5 7.2208 6.58 7.5499 6.73C7.1921 6.22 7 5.62 7 5C7 3.34 8.3431 2 10 2C11.4819 2 12.7418 3.08 12.9656 4.55C13.4349 3.89 14.1926 3.5 15 3.5C16.3807 3.5 17.5 4.62 17.5 6C17.5 6.17 17.483 6.34 17.4494 6.5C17.4663 6.5 17.4831 6.5 17.5 6.5C18.8807 6.5 20 7.62 20 9C20 9.79 19.6295 10.53 19 11M9 11L10 22M15 11L14 22M4 11H20L18.2986 20.36C18.1257 21.31 17.2974 22 16.3308 22H7.6692C6.7026 22 5.8743 21.31 5.7014 20.36L4 11Z");
}

</style>
