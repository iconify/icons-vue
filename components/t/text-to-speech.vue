<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/e-ab50cow.css';
import '../../css/q/q6a7scmtz.css';
import '../../css/k/kxv6pebud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="e-ab50cow"/><path class="q6a7scmtz"/><path class="kxv6pebud"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:text-to-speech" /></template>
