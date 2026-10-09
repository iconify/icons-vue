<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmcricc-j.css';
import '../../css/k/kkd7-e-we.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pmcricc-j"/><path class="kkd7-e-we"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-plug-48-bold" /></template>
