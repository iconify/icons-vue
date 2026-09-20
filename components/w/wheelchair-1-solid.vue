<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wymxdlcbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wymxdlcbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:wheelchair-1-solid" /></template>
