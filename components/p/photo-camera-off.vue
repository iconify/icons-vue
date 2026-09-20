<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i1fv7cbto.css';
import '../../css/k/kd2cqsb_l.css';
import '../../css/s/spe8wybxg.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="i1fv7cbto"/><path clip-rule="evenodd" class="kd2cqsb_l"/><path clip-rule="evenodd" class="spe8wybxg"/><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:photo-camera-off" /></template>
