<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cas7lohbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-week-outline-sharp" /></template>
<style>
.cas7lohbe {
  fill: currentColor;
  d: path("M4 18h4.673V6H4zm5.673 0h4.654V6H9.673zm5.654 0H20V6h-4.673zM21 19H3V5h18z");
}

</style>
