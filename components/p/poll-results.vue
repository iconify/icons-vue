<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo67xg7hi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jo67xg7hi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:poll-results" /></template>
