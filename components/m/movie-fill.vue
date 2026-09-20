<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqd6-1bqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqd6-1bqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:movie-fill" /></template>
