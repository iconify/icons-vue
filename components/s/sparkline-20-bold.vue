<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v945mrjcg.css';
import '../../css/l/l2m0plbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v945mrjcg"/><path class="l2m0plbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sparkline-20-bold" /></template>
