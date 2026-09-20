<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0y6rabqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0y6rabqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:tally-3" /></template>
