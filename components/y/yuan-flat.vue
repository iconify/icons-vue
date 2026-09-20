<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7p5xrztk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z7p5xrztk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:yuan-flat" /></template>
