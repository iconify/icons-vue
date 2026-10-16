<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udb4q3cvm.css';
import '../../css/k/k4f35ou0d.css';
import '../../css/e/e8_sa6eqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="udb4q3cvm"/><path class="k4f35ou0d"/><path class="e8_sa6eqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mail-search-20-bold" /></template>
