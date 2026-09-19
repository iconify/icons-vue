<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrjct8wjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yrjct8wjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:reddit-alien" /></template>
