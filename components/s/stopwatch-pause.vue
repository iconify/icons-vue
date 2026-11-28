<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_dm_4bhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_dm_4bhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:stopwatch-pause" /></template>
