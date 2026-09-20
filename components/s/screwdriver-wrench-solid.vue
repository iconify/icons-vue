<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds6j52bpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ds6j52bpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:screwdriver-wrench-solid" /></template>
