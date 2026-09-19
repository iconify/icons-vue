<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn2k2obiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xn2k2obiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:search" /></template>
