<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia064d6jl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ia064d6jl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:pine-tree" /></template>
