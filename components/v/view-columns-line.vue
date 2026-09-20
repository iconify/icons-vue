<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6q8vjbqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6q8vjbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:view-columns-line" /></template>
