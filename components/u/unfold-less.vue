<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6diiztnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":200,"height":384};
const content = `<path class="n6diiztnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:unfold-less" /></template>
