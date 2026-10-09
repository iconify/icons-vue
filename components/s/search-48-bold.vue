<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-pfn5jar.css';
import '../../css/n/nben1wb6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u-pfn5jar"/><path class="nben1wb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:search-48-bold" /></template>
