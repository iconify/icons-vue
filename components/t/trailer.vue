<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/n/nz1wz29-n.css';
import '../../css/u/uwpdhwbvk.css';
import '../../css/w/wh2bzxdhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nz1wz29-n"/><path class="uwpdhwbvk"/><circle class="wh2bzxdhv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:trailer" /></template>
