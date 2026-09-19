<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/z/zqbpy6boz.css';
import '../../css/z/zuoznrbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="n1lsf0bnc"><path class="zqbpy6boz"/><path class="zuoznrbss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:slider-round-1" /></template>
