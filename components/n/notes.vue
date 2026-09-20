<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0p5jxc6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="u0p5jxc6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:notes" /></template>
