<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruvbg847r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ruvbg847r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:vending-chemist" /></template>
