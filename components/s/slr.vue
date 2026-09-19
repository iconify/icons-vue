<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f335a1bdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f335a1bdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:slr" /></template>
