<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkihj-w6g.css';
import '../../css/c/ce_vlmbjr.css';
import '../../css/a/al014_b-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rkihj-w6g"/><path class="ce_vlmbjr"/><path class="al014_b-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shield-x-20" /></template>
