<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/coc31dbmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="coc31dbmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tag-search-outline" /></template>
