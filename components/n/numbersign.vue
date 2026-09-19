<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klmhtvbjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":555,"height":759};
const content = `<path class="klmhtvbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:numbersign" /></template>
