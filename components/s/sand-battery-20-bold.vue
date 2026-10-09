<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-akp5bab.css';
import '../../css/c/cl0ksvb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s-akp5bab"/><path class="cl0ksvb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sand-battery-20-bold" /></template>
