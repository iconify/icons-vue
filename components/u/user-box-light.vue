<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/e/e57ldqyuj.css';
import '../../css/p/pwbt2qflx.css';
import '../../css/j/jdy6ymapr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="e57ldqyuj"/><circle class="pwbt2qflx"/><rect class="jdy6ymapr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:user-box-light" /></template>
