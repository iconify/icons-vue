<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx6tlvbkb.css';
import '../../css/u/uk9yq28xx.css';
import '../../css/d/d3ye85bme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="tx6tlvbkb"><path class="uk9yq28xx"/><path class="d3ye85bme"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:socketio" /></template>
