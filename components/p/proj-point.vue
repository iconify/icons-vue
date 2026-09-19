<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uoccat2cq.css';
import '../../css/e/ev59uebdl.css';
import '../../css/i/imf56g2tr.css';
import '../../css/d/dy2dcuksu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<circle class="uoccat2cq"/><circle class="ev59uebdl"/><path class="imf56g2tr"/><path class="dy2dcuksu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:proj-point" /></template>
