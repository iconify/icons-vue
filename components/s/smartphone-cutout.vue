<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/o/onur_rgrp.css';
import '../../css/u/uub02fbik.css';
import '../../css/w/w1_hpxy5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="onur_rgrp"/><path class="uub02fbik"/><path class="w1_hpxy5f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:smartphone-cutout" /></template>
