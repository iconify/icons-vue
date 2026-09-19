<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkk--mbrq.css';
import '../../css/p/p1d__o_kt.css';
import '../../css/e/emz8u50dq.css';
import '../../css/m/mue43obit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xkk--mbrq"/><path class="p1d__o_kt"/><circle class="emz8u50dq"/><ellipse transform="rotate(33.488 194.39 60.752)" class="mue43obit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:roundpushpin" /></template>
