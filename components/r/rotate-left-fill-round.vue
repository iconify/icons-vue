<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol5qor7ho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ol5qor7ho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rotate-left-fill-round" /></template>
