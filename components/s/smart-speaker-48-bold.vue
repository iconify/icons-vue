<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmd-k42xk.css';
import '../../css/g/gbbj8_bmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wmd-k42xk"/><path class="gbbj8_bmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-speaker-48-bold" /></template>
