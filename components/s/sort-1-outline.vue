<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eiarx5bwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="eiarx5bwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sort-1-outline" /></template>
