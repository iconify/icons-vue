<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7u7phbli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7u7phbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:paint-bucket" /></template>
