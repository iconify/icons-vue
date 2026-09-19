<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1h899aoi.css';
import '../../css/w/w11ykpb4l.css';
import '../../css/q/q8ei_comh.css';
import '../../css/w/wg4j_ojiz.css';
import '../../css/k/khko_1cpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="k1h899aoi"/><path class="w11ykpb4l"/><path class="q8ei_comh"/><path class="wg4j_ojiz"/><path class="khko_1cpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:mobx" /></template>
