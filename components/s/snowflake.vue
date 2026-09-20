<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgq6vk-7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zgq6vk-7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:snowflake" /></template>
