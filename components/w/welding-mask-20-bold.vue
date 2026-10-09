<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3t3vqbie.css';
import '../../css/u/uook0dnzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a3t3vqbie"/><path class="uook0dnzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:welding-mask-20-bold" /></template>
