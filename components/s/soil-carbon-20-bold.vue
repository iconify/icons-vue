<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz6pfccwf.css';
import '../../css/k/kwpuslbzu.css';
import '../../css/d/d4ypccbfw.css';
import '../../css/j/j-7gwtb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iz6pfccwf"/><path class="kwpuslbzu"/><path class="d4ypccbfw"/><path class="j-7gwtb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:soil-carbon-20-bold" /></template>
