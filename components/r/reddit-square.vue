<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppamt2b3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="ppamt2b3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:reddit-square" /></template>
