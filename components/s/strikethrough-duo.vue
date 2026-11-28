<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/tltjt5b_s.css';
import '../../css/o/o6kj8tx6m.css';
import '../../css/h/hm0ch0kmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="tltjt5b_s"/><path class="o6kj8tx6m"/><path class="hm0ch0kmd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:strikethrough-duo" /></template>
