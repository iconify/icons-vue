<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yowz-bcyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yowz-bcyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:wheat" /></template>
