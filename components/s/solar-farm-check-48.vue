<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9ufck1xu.css';
import '../../css/o/oc4c5hbmp.css';
import '../../css/q/qdytrdbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e9ufck1xu"/><path class="oc4c5hbmp"/><path class="qdytrdbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-farm-check-48" /></template>
