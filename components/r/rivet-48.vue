<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvj4h6twa.css';
import '../../css/s/sy5tukbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lvj4h6twa"/><path class="sy5tukbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rivet-48" /></template>
