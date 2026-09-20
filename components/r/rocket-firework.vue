<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7ogqu_4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j7ogqu_4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:rocket-firework" /></template>
