<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7slukbjf.css';
import '../../css/h/hyz9tubor.css';
import '../../css/y/yu8ceqbjs.css';
import '../../css/q/q425r9b_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u7slukbjf"/><path class="hyz9tubor"/><path class="yu8ceqbjs"/><path class="q425r9b_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pressure-gauge-20-bold" /></template>
