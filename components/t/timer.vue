<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwww74b4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vwww74b4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:timer" /></template>
