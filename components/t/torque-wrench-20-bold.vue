<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk1wv8bbc.css';
import '../../css/g/ggz3dxbtl.css';
import '../../css/o/ok4v_yuxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mk1wv8bbc"/><path class="ggz3dxbtl"/><path class="ok4v_yuxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:torque-wrench-20-bold" /></template>
