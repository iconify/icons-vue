<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vawxl5b6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-arrow-up-right-sharp-fill" /></template>
<style>
.vawxl5b6j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2L21 2C21.5523 2 22 2.4477 22 3L22 17C22 17.5523 21.5523 18 21 18L7.4142 18L3.7071 21.7071C3.5196 21.8946 3.2652 22 3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.4477 2.4477 2 3 2ZM12.5858 8L8.2929 12.2929L8 12.5858L9.4142 14L9.7071 13.7071L14 9.4142L14 13L14 14L16 14L16 13L16 7C16 6.4477 15.5523 6 15 6L9 6L8 6L8 8L9 8Z");
}

</style>
