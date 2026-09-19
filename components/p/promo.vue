<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hza2asblm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":480,"height":496};
const content = `<path class="hza2asblm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:promo" /></template>
