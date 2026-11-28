<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dc--c-byw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dc--c-byw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:soda-can" /></template>
