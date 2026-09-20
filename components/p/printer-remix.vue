<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c11q6xlgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c11q6xlgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:printer-remix" /></template>
