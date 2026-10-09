<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ioqh6lbvj.css';
import '../../css/n/nhtywxbko.css';
import '../../css/q/qz4s_4byz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ioqh6lbvj"/><path class="nhtywxbko"/><path class="qz4s_4byz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:paint-bucket-20-bold" /></template>
