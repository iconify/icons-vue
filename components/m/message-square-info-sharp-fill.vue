<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mz93espmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-info-sharp-fill" /></template>
<style>
.mz93espmd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2L21 2C21.5523 2 22 2.4477 22 3L22 17C22 17.5523 21.5523 18 21 18L7.4142 18L3.7071 21.7071C3.5196 21.8946 3.2652 22 3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.4477 2.4477 2 3 2ZM13 14L13 13L13 11L13 10L11 10L11 11L11 13L11 14ZM13 7C13 6.4477 12.5523 6 12 6C11.4477 6 11 6.4477 11 7C11 7.5523 11.4477 8 12 8C12.5523 8 13 7.5523 13 7Z");
}

</style>
