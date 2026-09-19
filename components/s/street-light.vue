<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/x/xgtstcblw.css';
import '../../css/z/zxllwrblm.css';
import '../../css/m/ms-hx8b4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="wwvp95byt"><path class="xgtstcblw"/><path class="zxllwrblm"/><path class="ms-hx8b4m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:street-light" /></template>
