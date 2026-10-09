<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqiswsboe.css';
import '../../css/r/rynce1opb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kqiswsboe"/><path class="rynce1opb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:music-48-bold" /></template>
