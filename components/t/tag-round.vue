<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1jxzf26l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1jxzf26l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tag-round" /></template>
