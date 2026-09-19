<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkgg58bfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fkgg58bfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:trash3-fill" /></template>
