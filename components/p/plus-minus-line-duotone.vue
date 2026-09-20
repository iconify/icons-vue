<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/jsj8gunlj.css';
import '../../css/m/mzmeouzvr.css';
import '../../css/i/ifpcpz80t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jsj8gunlj"/><path class="mzmeouzvr"/><path class="ifpcpz80t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:plus-minus-line-duotone" /></template>
