<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_ah50reo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e_ah50reo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:prisma" /></template>
