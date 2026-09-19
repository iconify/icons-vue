<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m79_piezz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m79_piezz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:strat" /></template>
