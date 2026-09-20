<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml10vowlz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ml10vowlz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:shopping-cart" /></template>
