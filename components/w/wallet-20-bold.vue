<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8ckwu0tw.css';
import '../../css/q/qgpi-ab8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s8ckwu0tw"/><path class="qgpi-ab8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wallet-20-bold" /></template>
