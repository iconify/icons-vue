<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxdmc1b5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxdmc1b5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:refrigerator-filled-bottom" /></template>
