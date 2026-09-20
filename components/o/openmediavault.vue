<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrvfbr9fo.css';
import '../../css/r/r-62_47-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mrvfbr9fo"/><path class="r-62_47-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openmediavault" /></template>
