<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr22n6bpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yr22n6bpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:parenthesis-right-duo" /></template>
