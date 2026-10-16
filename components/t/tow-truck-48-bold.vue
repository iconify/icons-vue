<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy406sb7c.css';
import '../../css/e/e1grfmb0c.css';
import '../../css/r/rb4cb762a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cy406sb7c"/><path class="e1grfmb0c"/><path class="rb4cb762a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tow-truck-48-bold" /></template>
