<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0et9ft_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0et9ft_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:unfold-vertical" /></template>
