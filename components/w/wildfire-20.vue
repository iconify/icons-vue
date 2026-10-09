<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8uy6ybjb.css';
import '../../css/b/bx-b5ccfa.css';
import '../../css/p/pycxazbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o8uy6ybjb"/><path class="bx-b5ccfa"/><path class="pycxazbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wildfire-20" /></template>
