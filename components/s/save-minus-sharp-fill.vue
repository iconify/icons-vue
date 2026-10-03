<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="agldvyntg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:save-minus-sharp-fill" /></template>
<style>
.agldvyntg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 2L17 2C17.2652 2 17.5196 2.1054 17.7071 2.2929L21.7071 6.2929C21.8946 6.4804 22 6.7348 22 7L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.4477 2.4477 2 3 2ZM7 4L7 7L13 7L13 4L7 4ZM8 13L8 15L16 15L16 13L8 13Z");
}

</style>
