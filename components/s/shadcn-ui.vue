<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8c9qb1jl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b p8c9qb1jl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:shadcn-ui" /></template>
