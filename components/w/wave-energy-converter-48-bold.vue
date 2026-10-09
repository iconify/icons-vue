<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/liot4-bzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="liot4-bzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wave-energy-converter-48-bold" /></template>
