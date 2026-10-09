<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmcrjabqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dmcrjabqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:woodchip-20-bold" /></template>
