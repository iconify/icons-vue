<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vhzaqsb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-point-bold" /></template>
<style>
.vhzaqsb0a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2C16.4183 2 20 6.00258 20 10.5C20 14.9622 17.4466 19.8128 13.4629 21.6748C12.5343 22.1088 11.4657 22.1088 10.5371 21.6748C6.55337 19.8128 4 14.9622 4 10.5C4 6.00258 7.58172 2 12 2ZM12 7C10.3431 7 9 8.34315 9 10C9 11.6569 10.3431 13 12 13C13.6569 13 15 11.6569 15 10C15 8.34315 13.6569 7 12 7Z");
}

</style>
