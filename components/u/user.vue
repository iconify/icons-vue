<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jiir3lbjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jiir3lbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:user" /></template>
