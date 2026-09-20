<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9045w0jl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i9045w0jl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-sleeping-in-bed-between-floor-and-ceiling" /></template>
