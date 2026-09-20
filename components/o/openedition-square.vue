<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfkexgkrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="kfkexgkrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:openedition-square" /></template>
