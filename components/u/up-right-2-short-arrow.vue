<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqn01wbgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqn01wbgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:up-right-2-short-arrow" /></template>
