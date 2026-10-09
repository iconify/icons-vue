<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l94bcicug.css';
import '../../css/b/bjyphubzh.css';
import '../../css/f/ffcx5ccbi.css';
import '../../css/f/ffv-oibsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l94bcicug"/><path class="bjyphubzh"/><path class="ffcx5ccbi"/><path class="ffv-oibsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-tracker-20" /></template>
