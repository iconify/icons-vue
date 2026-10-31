<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8yi0vlry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8yi0vlry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:signal-medium-fill-round" /></template>
