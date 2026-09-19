<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/w/wg4wfrbba.css';
import '../../css/c/c_8zr8hod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<g class="h01tyzbfu"><circle class="wg4wfrbba"/><path class="c_8zr8hod"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:user-solo-stroke-12" /></template>
