<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj4_kbeau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zj4_kbeau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:smartphone-lock" /></template>
