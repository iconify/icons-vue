<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upgv8zb1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upgv8zb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:salad" /></template>
