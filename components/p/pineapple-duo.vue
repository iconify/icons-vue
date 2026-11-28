<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1-cm4brz.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/whtvn7boo.css';
import '../../css/d/d8v54zgrd.css';
import '../../css/s/s7l4crbfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1-cm4brz secondary"/><g class="dt0cm9dhy primary"><path class="whtvn7boo"/><path class="d8v54zgrd"/><path class="s7l4crbfx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pineapple-duo" /></template>
