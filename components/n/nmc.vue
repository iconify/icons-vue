<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4e0ujhru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h4e0ujhru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:nmc" /></template>
