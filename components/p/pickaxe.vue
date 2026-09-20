<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu9465z8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="nu9465z8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:pickaxe" /></template>
