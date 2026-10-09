<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt37rybne.css';
import '../../css/t/tpzkgwbum.css';
import '../../css/v/vargdwkro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vt37rybne"/><path class="tpzkgwbum"/><path class="vargdwkro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mine-shaft-48-bold" /></template>
