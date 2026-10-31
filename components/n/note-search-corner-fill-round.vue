<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5p_60bsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5p_60bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-search-corner-fill-round" /></template>
