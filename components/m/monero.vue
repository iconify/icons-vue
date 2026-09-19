<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/galr4-yxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="galr4-yxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:monero" /></template>
