<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fph3g9b8f.css';
import '../../css/g/g4fgyobiq.css';
import '../../css/q/q5x211bex.css';
import '../../css/i/ikv4dbcut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fph3g9b8f"/><path class="g4fgyobiq"/><path class="q5x211bex"/><path class="ikv4dbcut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sliders-20-bold" /></template>
