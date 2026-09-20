<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czoxhcbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czoxhcbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:moon-stars-fill" /></template>
