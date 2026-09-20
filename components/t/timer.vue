<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybsqveu6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybsqveu6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:timer" /></template>
