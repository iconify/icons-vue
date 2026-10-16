<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqpblyxmw.css';
import '../../css/g/g49fs7bzv.css';
import '../../css/u/u-hmmubte.css';
import '../../css/m/mkzjpdbji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wqpblyxmw"/><path class="g49fs7bzv"/><path class="u-hmmubte"/><path class="mkzjpdbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:satellite-dish-20" /></template>
