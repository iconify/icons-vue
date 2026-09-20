<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvyr4dczo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="fvyr4dczo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:quotation-2" /></template>
