<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y09lc3bln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y09lc3bln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:skip-previous" /></template>
