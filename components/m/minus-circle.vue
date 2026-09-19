<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3n2sxboq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3n2sxboq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:minus-circle" /></template>
