<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu_qqx5qu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fu_qqx5qu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:trend-down" /></template>
