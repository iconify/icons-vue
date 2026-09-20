<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3l9webvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3l9webvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:select" /></template>
