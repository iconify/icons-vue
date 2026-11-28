<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahhl9bcxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mail-search-sharp" /></template>
<style>
.ahhl9bcxy {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 20L2 20L2 4L22 4L22 11M2 7L11.2929 11C11.7154 11.2817 12.2846 11.2817 12.7071 11L22 7M21 16.5C21 17.8807 19.8807 19 18.5 19C17.1193 19 16 17.8807 16 16.5C16 15.1193 17.1193 14 18.5 14C19.8807 14 21 15.1193 21 16.5ZM20.2678 18.2678L22.2929 20.2929");
}

</style>
