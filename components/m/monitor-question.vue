<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-b6p1bze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-b6p1bze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:monitor-question" /></template>
