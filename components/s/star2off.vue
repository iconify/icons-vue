<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuvhlpdhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uuvhlpdhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:star2off" /></template>
