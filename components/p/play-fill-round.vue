<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/caz71cbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="caz71cbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:play-fill-round" /></template>
