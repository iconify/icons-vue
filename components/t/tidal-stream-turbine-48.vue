<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfm2ybc6q.css';
import '../../css/s/szotk6bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pfm2ybc6q"/><path class="szotk6bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tidal-stream-turbine-48" /></template>
