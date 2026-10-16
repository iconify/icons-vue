<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8mzgiwjz.css';
import '../../css/w/w43qocbxc.css';
import '../../css/d/d7ab7wboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u8mzgiwjz"/><path class="w43qocbxc"/><path class="d7ab7wboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:nuclear-plant-check-48" /></template>
