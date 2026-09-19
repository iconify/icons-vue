<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu42j5gbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":778,"height":739};
const content = `<path class="yu42j5gbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:star" /></template>
