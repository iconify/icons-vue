<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5cjirboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5cjirboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:share-forward-2-line" /></template>
