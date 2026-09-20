<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-lgg5lrv.css';
import '../../css/f/fbsjnybco.css';
import '../../css/q/q-97-wbjf.css';
import '../../css/m/mk2e5acas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="n-lgg5lrv"/><path class="fbsjnybco"/><path class="q-97-wbjf"/><path class="mk2e5acas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:straight-ruler" /></template>
