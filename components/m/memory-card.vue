<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pij_c5y_o.css';
import '../../css/g/g6bv-gb_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pij_c5y_o"/><path class="g6bv-gb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:memory-card" /></template>
