<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hojfg4bzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hojfg4bzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:stack-limitation" /></template>
