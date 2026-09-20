<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya239x24v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ya239x24v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:travel-map" /></template>
