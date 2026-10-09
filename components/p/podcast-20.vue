<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs5v-pa0a.css';
import '../../css/c/clh9fmvvs.css';
import '../../css/q/q_91rlk-i.css';
import '../../css/d/d28ovxb4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hs5v-pa0a"/><path class="clh9fmvvs"/><path class="q_91rlk-i"/><path class="d28ovxb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:podcast-20" /></template>
