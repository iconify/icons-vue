<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yftarabyl.css';
import '../../css/q/qxihk5bwn.css';
import '../../css/k/knu7vdbvo.css';
import '../../css/o/ofhs6z3pm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yftarabyl"/><path class="qxihk5bwn"/><path class="knu7vdbvo"/><path class="ofhs6z3pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-word-light" /></template>
