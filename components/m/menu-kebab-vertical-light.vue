<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuzkko4qn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tuzkko4qn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:menu-kebab-vertical-light" /></template>
