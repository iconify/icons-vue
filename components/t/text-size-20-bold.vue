<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsy-cw1ys.css';
import '../../css/o/o338q5bim.css';
import '../../css/k/k_q3cjb9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tsy-cw1ys"/><path class="o338q5bim"/><path class="k_q3cjb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:text-size-20-bold" /></template>
