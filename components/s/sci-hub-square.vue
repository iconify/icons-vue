<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh4xk2b5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="xh4xk2b5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:sci-hub-square" /></template>
