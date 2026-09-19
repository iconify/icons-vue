<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5f5msbrf.css';
import '../../css/d/dx3032ngj.css';
import '../../css/i/ibbuc4bji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d5f5msbrf"/><path class="dx3032ngj"/><path class="ibbuc4bji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:performingarts" /></template>
