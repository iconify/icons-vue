<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uea3lmbvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uea3lmbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:ribbon" /></template>
