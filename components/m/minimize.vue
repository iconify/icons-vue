<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyd5txbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gyd5txbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:minimize" /></template>
