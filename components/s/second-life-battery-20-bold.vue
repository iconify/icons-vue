<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq-2zqbgl.css';
import '../../css/x/xny_r4baq.css';
import '../../css/m/muekd2yie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nq-2zqbgl"/><path class="xny_r4baq"/><path class="muekd2yie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:second-life-battery-20-bold" /></template>
