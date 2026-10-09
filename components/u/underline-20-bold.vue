<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljsp6_b8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ljsp6_b8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:underline-20-bold" /></template>
