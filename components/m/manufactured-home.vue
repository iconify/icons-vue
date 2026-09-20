<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i42eqgbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i42eqgbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:manufactured-home" /></template>
