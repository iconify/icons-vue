<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx48pmbno.css';
import '../../css/j/j6ylgsbjb.css';
import '../../css/j/jtmiwfbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yx48pmbno"/><path class="j6ylgsbjb"/><path class="jtmiwfbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-pump-48-bold" /></template>
