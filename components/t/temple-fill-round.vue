<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgefz0bqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgefz0bqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:temple-fill-round" /></template>
