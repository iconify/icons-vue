<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skm13gbpu.css';
import '../../css/q/qt_17gbik.css';
import '../../css/g/g_wuh4bxx.css';
import '../../css/m/mpk28w9ff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="skm13gbpu"/><path class="qt_17gbik"/><path class="g_wuh4bxx"/><path class="mpk28w9ff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-farm-check-20" /></template>
