<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/h/h2po03bxv.css';
import '../../css/f/f1er5e3yx.css';
import '../../css/d/dw0vfobux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<g class="h01tyzbfu"><circle class="h2po03bxv"/><circle class="f1er5e3yx"/><path class="dw0vfobux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:voicemail-stroke-12" /></template>
