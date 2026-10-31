<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9ytbtbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9ytbtbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:playing-cards-round" /></template>
