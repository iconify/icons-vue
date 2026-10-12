<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mriwaebth.css';
import '../../css/q/q2a0nbcka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mriwaebth"/><path class="q2a0nbcka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:whiteboard-20" /></template>
