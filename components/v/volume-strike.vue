<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzgbc4l5y.css';
import '../../css/q/qebutnwnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="uzgbc4l5y"/><path class="qebutnwnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:volume-strike" /></template>
