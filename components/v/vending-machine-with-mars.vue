<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/derf13ncu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="derf13ncu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:vending-machine-with-mars" /></template>
