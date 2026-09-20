<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye7sjbc8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye7sjbc8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:user-arrow-right-outline" /></template>
