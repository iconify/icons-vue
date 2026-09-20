<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5ia4bbks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="w5ia4bbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:text-flow-rows" /></template>
