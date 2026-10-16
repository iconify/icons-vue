<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfoz5gb8g.css';
import '../../css/l/lndetpb3x.css';
import '../../css/o/ous0wrp5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vfoz5gb8g"/><path class="lndetpb3x"/><path class="ous0wrp5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:transition-piece-48-bold" /></template>
