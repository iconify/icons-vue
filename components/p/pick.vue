<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/k/kjc0fr6xx.css';
import '../../css/t/tzbmdywci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<g class="n1lsf0bnc"><path class="kjc0fr6xx"/><path class="tzbmdywci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:pick" /></template>
