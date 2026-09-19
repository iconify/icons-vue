<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r35ib4brc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r35ib4brc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:trending-down" /></template>
