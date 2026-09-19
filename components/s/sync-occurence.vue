<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddy_x1bgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ddy_x1bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:sync-occurence" /></template>
