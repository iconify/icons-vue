<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va0-blb8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="va0-blb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:music" /></template>
