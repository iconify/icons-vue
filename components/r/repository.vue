<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/cmps53bym.css';
import '../../css/v/vfu_1b34a.css';
import '../../css/a/a0qpe2bov.css';
import '../../css/z/zwovzli5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cmps53bym"/><path class="vfu_1b34a"/><path class="a0qpe2bov"/><path class="zwovzli5u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:repository" /></template>
