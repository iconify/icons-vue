<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sbs8qrbjk.css';
import '../../css/z/zfv58jbiu.css';
import '../../css/j/jcz1l13ji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="sbs8qrbjk"/><path class="zfv58jbiu"/><path class="jcz1l13ji"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:musical-score" /></template>
