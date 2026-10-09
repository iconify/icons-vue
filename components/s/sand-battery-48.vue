<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnddocber.css';
import '../../css/e/ensp0mbmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tnddocber"/><path class="ensp0mbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sand-battery-48" /></template>
