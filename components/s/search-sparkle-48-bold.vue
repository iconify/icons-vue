<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-pfn5jar.css';
import '../../css/w/w81pxdb-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u-pfn5jar"/><path class="w81pxdb-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:search-sparkle-48-bold" /></template>
