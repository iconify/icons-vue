<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugefbkbuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ugefbkbuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:rock-tall" /></template>
