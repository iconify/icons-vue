<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doko_h-hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="doko_h-hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-list-filter-solid" /></template>
