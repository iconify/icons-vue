<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty5a_vbpt.css';
import '../../css/u/ubxf06b4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ty5a_vbpt"/><path class="ubxf06b4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:panel-left-close-48" /></template>
