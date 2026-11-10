<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f30r4v8bi.css';
import '../../css/i/i8p3d6bjp.css';
import '../../css/z/z3mdksbjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="f30r4v8bi"><path class="i8p3d6bjp"/><path class="z3mdksbjk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:upsilon-capital" /></template>
