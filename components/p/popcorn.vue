<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymr-83eum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymr-83eum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:popcorn" /></template>
