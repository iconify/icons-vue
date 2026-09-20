<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umrigur1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umrigur1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:thumbs-down-fill" /></template>
