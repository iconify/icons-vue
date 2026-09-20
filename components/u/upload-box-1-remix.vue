<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd4ahsbfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dd4ahsbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:upload-box-1-remix" /></template>
