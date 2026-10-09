<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuvdc2bma.css';
import '../../css/w/ww4ol3fvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yuvdc2bma"/><path class="ww4ol3fvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:oscilloscope-48" /></template>
