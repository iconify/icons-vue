<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grbq68bib.css';
import '../../css/a/aqu--qbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="grbq68bib"/><path class="aqu--qbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tent-48" /></template>
