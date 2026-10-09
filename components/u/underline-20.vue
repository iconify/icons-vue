<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6ghr8bhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z6ghr8bhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:underline-20" /></template>
