<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aejzgobrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aejzgobrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-check-fill-round" /></template>
