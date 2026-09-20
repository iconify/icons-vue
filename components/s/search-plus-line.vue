<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft1jb2qms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft1jb2qms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:search-plus-line" /></template>
