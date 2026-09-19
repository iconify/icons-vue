<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9wy8vbyy.css';
import '../../css/q/qbotcdkoh.css';
import '../../css/r/rcv83i2oj.css';
import '../../css/h/hddayxb0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f9wy8vbyy"/><path class="qbotcdkoh"/><path class="rcv83i2oj"/><path class="hddayxb0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:pigsnout" /></template>
