<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/torobyboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="torobyboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:zodiac-pisces" /></template>
