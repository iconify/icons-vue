<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1e_f5blg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u1e_f5blg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:peak-shaving-48" /></template>
