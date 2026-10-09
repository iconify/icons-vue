<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovsz64b4d.css';
import '../../css/x/x46njsebn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ovsz64b4d"/><path class="x46njsebn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tidal-barrage-48" /></template>
