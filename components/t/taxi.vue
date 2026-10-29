<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/q1vr80fzk.css';
import '../../css/g/gsm21sbrt.css';
import '../../css/n/nb-vlvbbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="q1vr80fzk"/><path class="gsm21sbrt wm-a"/><path class="nb-vlvbbc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:taxi" /></template>
