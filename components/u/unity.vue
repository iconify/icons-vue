<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd_lskbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="zd_lskbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:unity" /></template>
