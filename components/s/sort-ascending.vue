<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhlyu95xx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhlyu95xx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:sort-ascending" /></template>
