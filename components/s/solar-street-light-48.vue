<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-ohmbl_e.css';
import '../../css/m/mhdsebbpt.css';
import '../../css/i/ib5meve9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o-ohmbl_e"/><path class="mhdsebbpt"/><path class="ib5meve9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-street-light-48" /></template>
