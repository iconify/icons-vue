<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybyhcbfuv.css';
import '../../css/e/eu08s8bww.css';
import '../../css/q/qwin8ubae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ybyhcbfuv"/><path class="eu08s8bww"/><path class="qwin8ubae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-speedometer" /></template>
