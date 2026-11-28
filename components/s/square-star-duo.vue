<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n12fu4gut.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/e77ebfb5e.css';
import '../../css/s/sunn0ibms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n12fu4gut secondary"/><g class="dt0cm9dhy primary"><path class="e77ebfb5e"/><path class="sunn0ibms"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-star-duo" /></template>
