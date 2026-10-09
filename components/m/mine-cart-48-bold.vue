<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez1ledqsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ez1ledqsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mine-cart-48-bold" /></template>
