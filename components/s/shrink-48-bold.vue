<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt2_w2b_f.css';
import '../../css/e/etdoy3bgw.css';
import '../../css/g/gc-e6wn8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jt2_w2b_f"/><path class="etdoy3bgw"/><path class="gc-e6wn8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shrink-48-bold" /></template>
