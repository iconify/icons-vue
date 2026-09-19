<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_g6_lbbk.css';
import '../../css/g/guoy00ruz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="s_g6_lbbk"/><path class="guoy00ruz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:stackoverflow" /></template>
