<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkkjs4bjp.css';
import '../../css/u/uwu_w82bn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkkjs4bjp"/><path class="uwu_w82bn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:swftc" /></template>
