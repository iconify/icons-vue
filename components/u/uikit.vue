<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":297};
const content = `<path class="j1zvzcp_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:uikit" /></template>
<style>
.j1zvzcp_v {
  fill: var(--svg-color--2396f3, #2396f3);
  d: path("M174.656 28.438L125.717 0L74.646 31.723l49.621 27.414zm23.403 12.245L147.52 71.424l57.28 33.109V192l-77.248 43.904L51.2 192v-68.267L0 98.304v123.563l125.717 74.666L256 222.422V74.155z");
}

</style>
