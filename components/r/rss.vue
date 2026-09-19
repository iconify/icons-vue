<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htf797bdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="htf797bdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:rss" /></template>
