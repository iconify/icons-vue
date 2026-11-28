<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l94dbb61v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l94dbb61v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:trophy" /></template>
