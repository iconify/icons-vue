<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg-e66htg.css';
import '../../css/a/abmkmib2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dg-e66htg"/><path class="abmkmib2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:nozzle-48" /></template>
