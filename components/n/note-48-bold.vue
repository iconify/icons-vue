<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl-eb8nlu.css';
import '../../css/l/l9u6gsyxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dl-eb8nlu"/><path class="l9u6gsyxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:note-48-bold" /></template>
