<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brtpu-bnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":22.5,"top":13.5};
const content = `<path class="brtpu-bnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vvveb-cms" /></template>
