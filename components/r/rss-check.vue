<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wn7jzcrio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wn7jzcrio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:rss-check" /></template>
