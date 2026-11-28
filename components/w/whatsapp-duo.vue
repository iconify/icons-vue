<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg6mp7bmo.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/p2yv41ddi.css';
import '../../css/s/stmbfjbtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg6mp7bmo secondary"/><g class="dt0cm9dhy primary"><path class="p2yv41ddi"/><path class="stmbfjbtn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:whatsapp-duo" /></template>
