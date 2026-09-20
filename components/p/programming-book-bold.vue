<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2d_vachs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2d_vachs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:programming-book-bold" /></template>
