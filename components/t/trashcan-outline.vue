<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np9o9uu-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="np9o9uu-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:trashcan-outline" /></template>
