<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjp48nbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="yjp48nbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:obp" /></template>
