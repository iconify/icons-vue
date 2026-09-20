<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es_julb3f.css';
import '../../css/f/fffoeubbe.css';
import '../../css/d/dxbo5w2dx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="es_julb3f"/><path class="fffoeubbe"/><path class="dxbo5w2dx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:sweat-droplets" /></template>
