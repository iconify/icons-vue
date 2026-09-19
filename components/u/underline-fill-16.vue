<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_3gb6obh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l_3gb6obh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:underline-fill-16" /></template>
