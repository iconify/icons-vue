<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytenn3bqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ytenn3bqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:terminal-stroke-20" /></template>
