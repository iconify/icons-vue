<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5dl38bxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="f5dl38bxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:sync-compact" /></template>
