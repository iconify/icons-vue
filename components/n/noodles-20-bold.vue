<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c03uu6r0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c03uu6r0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:noodles-20-bold" /></template>
