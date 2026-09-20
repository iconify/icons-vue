<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f14q2uffn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="f14q2uffn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:shift-flat" /></template>
