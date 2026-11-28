<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j96zg6bjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j96zg6bjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:office-building-plus" /></template>
