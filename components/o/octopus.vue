<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jowakrblr.css';
import '../../css/t/t2r34r-uy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jowakrblr"/><path class="t2r34r-uy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:octopus" /></template>
