<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hei8_htdz.css';
import '../../css/j/ju03a42fm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hei8_htdz"/><path class="ju03a42fm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:marker-gas-20-bold" /></template>
