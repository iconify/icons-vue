<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlpsal7ej.css';
import '../../css/m/mtg_mtnil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nlpsal7ej secondary"/><path class="mtg_mtnil primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-duo" /></template>
