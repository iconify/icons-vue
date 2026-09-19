<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxkpsmbop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="hxkpsmbop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:plus-square" /></template>
