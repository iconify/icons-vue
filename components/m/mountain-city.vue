<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywntjv63r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="ywntjv63r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:mountain-city" /></template>
