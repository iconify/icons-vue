<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9ufck1xu.css';
import '../../css/o/oc4c5hbmp.css';
import '../../css/i/ikpbwe38b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e9ufck1xu"/><path class="oc4c5hbmp"/><path class="ikpbwe38b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-farm-alert-48" /></template>
