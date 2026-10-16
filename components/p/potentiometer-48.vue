<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5ss8-b2m.css';
import '../../css/l/l1epn2jfk.css';
import '../../css/m/m82nk1bgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f5ss8-b2m"/><path class="l1epn2jfk"/><path class="m82nk1bgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:potentiometer-48" /></template>
