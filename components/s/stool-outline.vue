<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd0l-6ivh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sd0l-6ivh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:stool-outline" /></template>
