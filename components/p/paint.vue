<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdrjq2jwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vdrjq2jwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:paint" /></template>
