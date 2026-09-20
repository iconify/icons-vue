<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx6cf-bmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="wx6cf-bmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:puzzle-piece" /></template>
