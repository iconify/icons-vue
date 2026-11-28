<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujjy02v-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ujjy02v-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:music-notes-slash-thin" /></template>
