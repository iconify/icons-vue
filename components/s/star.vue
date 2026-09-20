<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc5zs_rrj.css';
import '../../css/d/da75vnbxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="vc5zs_rrj"/><path class="da75vnbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:star" /></template>
