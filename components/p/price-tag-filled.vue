<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eeak2jbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eeak2jbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:price-tag-filled" /></template>
