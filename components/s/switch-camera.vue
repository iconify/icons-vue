<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/i/it5js_8rn.css';
import '../../css/g/gp0egaclj.css';
import '../../css/h/hwlwzjglt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="it5js_8rn"/><circle class="gp0egaclj"/><path class="hwlwzjglt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:switch-camera" /></template>
