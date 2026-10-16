<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur2lebcua.css';
import '../../css/y/y82qmibcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ur2lebcua"/><path class="y82qmibcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:meter-cabinet-48-bold" /></template>
