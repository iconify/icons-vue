<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvmytbbgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvmytbbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:tickets" /></template>
