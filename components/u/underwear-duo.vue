<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3mnygnvh.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/p9qo8bcky.css';
import '../../css/z/za6iimbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3mnygnvh secondary"/><g class="dt0cm9dhy primary"><path class="p9qo8bcky"/><path class="za6iimbye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:underwear-duo" /></template>
