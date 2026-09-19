<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9kyeodza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9kyeodza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:stop-1" /></template>
