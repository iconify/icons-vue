<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfr-qx6ii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="qfr-qx6ii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:scanner-bar-code" /></template>
