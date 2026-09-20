<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9hkj_brj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:priority-high-rounded" /></template>
<style>
.w9hkj_brj {
  fill: currentColor;
  d: path("M12 18.846q-.413 0-.706-.293T11 17.846t.294-.706t.706-.294t.706.294t.294.706t-.294.707t-.706.293m-.003-3.807q-.303 0-.515-.215t-.213-.516V4.885q0-.302.216-.516t.518-.215t.515.215t.213.516v9.423q0 .301-.216.516q-.215.215-.518.215");
}

</style>
