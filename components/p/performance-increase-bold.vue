<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uferroy5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uferroy5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:performance-increase-bold" /></template>
