<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tirtiacjr.css';
import '../../css/h/hvucwhbtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tirtiacjr"/><path class="hvucwhbtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:switchgear-20-bold" /></template>
