<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6iikjgcv.css';
import '../../css/g/g2svsm15l.css';
import '../../css/z/z04drlb1l.css';
import '../../css/r/rmgjt6byk.css';
import '../../css/j/jii6c3x9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="s6iikjgcv"/><path class="g2svsm15l"/><g class="z04drlb1l"><path class="rmgjt6byk"/><path class="jii6c3x9u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:smiling-face-with-hearts" /></template>
