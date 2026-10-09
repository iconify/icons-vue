<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwjx20d_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jwjx20d_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:navigation-off-20-bold" /></template>
