<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l35scy-hf.css';
import '../../css/y/yekygsb-g.css';
import '../../css/p/pycxazbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l35scy-hf"/><path class="yekygsb-g"/><path class="pycxazbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tension-leg-20" /></template>
