<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h10oigbig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h10oigbig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:skis-48-bold" /></template>
