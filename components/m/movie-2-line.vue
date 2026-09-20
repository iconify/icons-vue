<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajnaei5ta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajnaei5ta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:movie-2-line" /></template>
