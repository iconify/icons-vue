<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mhumw6gqn.css';
import '../../css/o/o15o6ybrc.css';
import '../../css/j/jsjx8bc7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="mhumw6gqn"/><path class="o15o6ybrc"/><path class="jsjx8bc7k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:windsock" /></template>
