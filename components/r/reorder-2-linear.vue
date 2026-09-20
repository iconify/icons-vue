<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/pt6j8yqtd.css';
import '../../css/a/a13beybmo.css';
import '../../css/f/fgizidusj.css';
import '../../css/y/yjjibyi4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pt6j8yqtd"/><path class="a13beybmo"/><path class="fgizidusj"/><path class="yjjibyi4l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:reorder-2-linear" /></template>
