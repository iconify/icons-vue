<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jd-x16bws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:timer-fast-sharp" /></template>
<style>
.jd-x16bws {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.3699 8.2986L6.7085 8C8.1699 6.7112 10.0515 6 12 6C16.4183 6 20 9.5817 20 14C20 18.4183 16.4183 22 12 22C10.0515 22 8.1699 21.2888 6.7085 20L6.3699 19.7014M8 2L16 2M12 2L12 6M12 15L12 9M17.6569 8.3431L19.2929 6.7071M3 12L9 12M3 16L8 16");
}

</style>
