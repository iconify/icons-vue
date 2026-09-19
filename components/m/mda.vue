<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg6z65b8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bg6z65b8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:mda" /></template>
