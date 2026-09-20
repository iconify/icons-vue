<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw0ywobnf.css';
import '../../css/i/i06twubnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="pw0ywobnf"/><path clip-rule="evenodd" class="i06twubnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:sliders-horizontal-square-2" /></template>
