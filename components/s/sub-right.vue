<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysoeexjns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysoeexjns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:sub-right" /></template>
