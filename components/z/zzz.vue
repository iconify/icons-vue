<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doj9dq_jg.css';
import '../../css/e/ehv3lsbxi.css';
import '../../css/h/hb8m0waiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<g class="doj9dq_jg"><path class="ehv3lsbxi"/><path class="hb8m0waiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:zzz" /></template>
