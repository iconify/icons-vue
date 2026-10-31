<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uah-6e1tm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uah-6e1tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rocket-fill-round" /></template>
