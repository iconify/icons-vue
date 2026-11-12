<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gwely914n"/><path class="eg-wi4b5c"/><path class="vltoy5rhv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:money-bag-broken" /></template>
<style>
.eg-wi4b5c {
  d: path("M12 2C13.8856 2 14.8284 2 15.4142 2.58579C16 3.17157 16 4.11438 16 6M8 6C8 4.11438 8 3.17157 8.58579 2.58579");
}

.gwely914n {
  d: path("M3.17157 20.8284C4.34314 22 6.22876 22 9.99998 22H10H14H14C17.7712 22 19.6569 22 20.8284 20.8284C22 19.6569 22 17.7712 22 14C22 12.8302 22 11.8419 21.965 11M20.8284 7.17157C19.6569 6 17.7712 6 14 6H10C6.22876 6 4.34315 6 3.17157 7.17157C2 8.34315 2 10.2288 2 14C2 15.1698 2 16.1581 2.03496 17");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vltoy5rhv {
  d: path("M12 10.6667C10.8954 10.6667 10 11.4129 10 12.3333C10 13.2538 10.8954 14 12 14C13.1046 14 14 14.7462 14 15.6667C14 16.5871 13.1046 17.3333 12 17.3333M12 10.6667C13.1046 10.6667 14 11.4129 14 12.3333M12 10.6667V10M12 17.3333C10.8954 17.3333 10 16.5871 10 15.6667M12 17.3333V18");
}

</style>
