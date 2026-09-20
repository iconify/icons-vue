<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aq3_x3yyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aq3_x3yyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ollama" /></template>
