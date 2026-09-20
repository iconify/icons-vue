<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dnv2f5t7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:more-horizontal-48-regular" /></template>
<style>
.dnv2f5t7a {
  fill: currentColor;
  d: path("M15.752 24a3.25 3.25 0 1 1-6.5 0a3.25 3.25 0 0 1 6.5 0m11.5 0a3.25 3.25 0 1 1-6.5 0a3.25 3.25 0 0 1 6.5 0m8.25 3.25a3.25 3.25 0 1 0 0-6.5a3.25 3.25 0 0 0 0 6.5");
}

</style>
