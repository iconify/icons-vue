<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mutfufb4a.css';
import '../../css/e/eo5ryvbqs.css';
import '../../css/t/tjrjm1bac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mutfufb4a"/><path class="eo5ryvbqs"/><path class="tjrjm1bac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wine-glass-48-bold" /></template>
