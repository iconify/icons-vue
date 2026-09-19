<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfub6qbjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="vfub6qbjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:repeat-all" /></template>
