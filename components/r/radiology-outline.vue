<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhn1d58yx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhn1d58yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:radiology-outline" /></template>
