<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdz4u38km.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pdz4u38km"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:minimize-48" /></template>
