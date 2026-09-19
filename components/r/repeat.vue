<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw1d3gbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="bw1d3gbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:repeat" /></template>
