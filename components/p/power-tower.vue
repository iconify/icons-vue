<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxh2dlwch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wxh2dlwch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:power-tower" /></template>
