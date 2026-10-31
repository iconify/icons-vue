<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwub9tb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwub9tb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zoom-in-fill-round" /></template>
