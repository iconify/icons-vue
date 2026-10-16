<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4mm3xvgd.css';
import '../../css/p/pycxazbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m4mm3xvgd"/><path class="pycxazbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smog-20" /></template>
