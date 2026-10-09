<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn698acuz.css';
import '../../css/q/qyfrutbua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mn698acuz"/><path class="qyfrutbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tv-20-bold" /></template>
