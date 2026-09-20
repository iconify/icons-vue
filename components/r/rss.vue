<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl7y_pp3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl7y_pp3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:rss" /></template>
