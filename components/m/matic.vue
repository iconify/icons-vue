<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubh594mea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ubh594mea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:matic" /></template>
