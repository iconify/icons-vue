<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/o/ofg3t4b1p.css';
import '../../css/b/b64l0dbmf.css';
import '../../css/f/fj9t29bka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ofg3t4b1p"/><path class="b64l0dbmf"/><path class="fj9t29bka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:rotate-camera-right" /></template>
