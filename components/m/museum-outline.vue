<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azgyuxb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azgyuxb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:museum-outline" /></template>
