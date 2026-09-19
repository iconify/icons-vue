<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/i/if8avqb2l.css';
import '../../css/x/x-hw30lbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="n1lsf0bnc"><path class="if8avqb2l"/><path class="x-hw30lbb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:wtc" /></template>
