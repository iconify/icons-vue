<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajaek5qjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajaek5qjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:smart-watch" /></template>
