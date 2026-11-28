<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze2jbkbwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ze2jbkbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:window-lock" /></template>
