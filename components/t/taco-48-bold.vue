<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0l5ivb9x.css';
import '../../css/u/umgrjh4bj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p0l5ivb9x"/><path class="umgrjh4bj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:taco-48-bold" /></template>
