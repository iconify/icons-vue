<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz29xlien.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wz29xlien"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:metro-20-bold" /></template>
