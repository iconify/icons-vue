<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3c3hc3rv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3c3hc3rv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sort-numeric-descending" /></template>
