<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd6fc7nov.css';
import '../../css/m/mxvx73bzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pd6fc7nov"/><path class="mxvx73bzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:video-off-48" /></template>
