<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjfal4j5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sjfal4j5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:toilet-man-flat" /></template>
