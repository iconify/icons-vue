<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz3-ulbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hz3-ulbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:menu" /></template>
