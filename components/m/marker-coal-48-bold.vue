<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etlms99xu.css';
import '../../css/c/c4c6vbbnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="etlms99xu"/><path class="c4c6vbbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:marker-coal-48-bold" /></template>
