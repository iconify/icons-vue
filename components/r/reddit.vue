<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjh784b5x.css';
import '../../css/c/cx2ml4bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="hjh784b5x"/><path class="cx2ml4bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:reddit" /></template>
