<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djw0pcgoi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djw0pcgoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:shield" /></template>
