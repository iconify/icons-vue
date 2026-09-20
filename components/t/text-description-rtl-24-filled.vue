<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfmoaqbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-description-rtl-24-filled" /></template>
<style>
.rfmoaqbwi {
  fill: currentColor;
  d: path("M21 17H9a1 1 0 0 0-.117 1.993L9 19h12a1 1 0 0 0 .117-1.993zH9zm0-4H3a1 1 0 0 0-.117 1.993L3 15h18a1 1 0 0 0 .117-1.993zH3zm0-4H3a1 1 0 0 0-.117 1.993L3 11h18a1 1 0 0 0 .117-1.993zH3zm0-4H3a1 1 0 0 0-.117 1.993L3 7h18a1 1 0 0 0 .117-1.993zH3z");
}

</style>
