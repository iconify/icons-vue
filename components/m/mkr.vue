<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iksa7qb8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iksa7qb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:mkr" /></template>
