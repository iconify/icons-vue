<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0fks5-0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j0fks5-0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:streets-nav" /></template>
