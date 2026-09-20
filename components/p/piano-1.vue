<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzh21_idx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzh21_idx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:piano-1" /></template>
