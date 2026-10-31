<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5liy5rbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5liy5rbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sort-a-z-fill-round" /></template>
