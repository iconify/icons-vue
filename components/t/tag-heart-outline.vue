<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ceqzzwbhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ceqzzwbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tag-heart-outline" /></template>
