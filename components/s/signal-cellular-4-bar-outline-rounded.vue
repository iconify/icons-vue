<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg34kmehp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:signal-cellular-4-bar-outline-rounded" /></template>
<style>
.gg34kmehp {
  fill: currentColor;
  d: path("M4.598 21q-.315 0-.488-.204q-.172-.204-.172-.475q0-.137.037-.235t.148-.209L19.877 4.123q.112-.111.21-.148t.233-.036q.272 0 .476.172t.204.487v15.479q0 .385-.27.654t-.653.269z");
}

</style>
