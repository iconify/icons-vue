<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc5lbibdl.css';
import '../../css/w/wna2nnb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kc5lbibdl"/><path class="wna2nnb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:volume-high-48-bold" /></template>
