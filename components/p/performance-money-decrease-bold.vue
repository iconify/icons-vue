<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxzp69sea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxzp69sea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:performance-money-decrease-bold" /></template>
