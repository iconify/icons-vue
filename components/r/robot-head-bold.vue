<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivu72hdvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ivu72hdvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:robot-head-bold" /></template>
