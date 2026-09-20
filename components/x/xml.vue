<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymiz41-qh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymiz41-qh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:xml" /></template>
