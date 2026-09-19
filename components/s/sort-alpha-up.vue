<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye7an4k6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ye7an4k6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sort-alpha-up" /></template>
