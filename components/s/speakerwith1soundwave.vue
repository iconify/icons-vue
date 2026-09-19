<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7kd4zr2m.css';
import '../../css/g/gc3rb1bxv.css';
import '../../css/r/rortcs8ut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v7kd4zr2m"/><path class="gc3rb1bxv"/><path class="rortcs8ut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:speakerwith1soundwave" /></template>
