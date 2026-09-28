<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phndsllga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:timer-fast" /></template>
<style>
.phndsllga {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.7085 8C8.1699 6.7112 10.0515 6 12 6C16.4183 6 20 9.5817 20 14C20 18.4183 16.4183 22 12 22C10.0515 22 8.1699 21.2888 6.7085 20M9 2L15 2M12 2L12 6M12 14L12 10M17.6569 8.3431L19 7M4 12L8 12M4 16L7 16");
}

</style>
