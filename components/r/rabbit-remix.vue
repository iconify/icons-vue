<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u82v2_bzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u82v2_bzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:rabbit-remix" /></template>
