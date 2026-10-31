<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg1bm570r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg1bm570r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-plus-fill-round" /></template>
