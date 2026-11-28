<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1lne0b2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1lne0b2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:package-x" /></template>
