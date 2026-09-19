<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uax-zvfsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="uax-zvfsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:money-bag-usd" /></template>
