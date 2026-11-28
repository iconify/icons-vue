<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfmk6ub6x.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/whxzr4veb.css';
import '../../css/k/kzir-9buk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfmk6ub6x secondary"/><g class="dt0cm9dhy primary"><path class="whxzr4veb"/><path class="kzir-9buk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:zodiac-leo-duo" /></template>
