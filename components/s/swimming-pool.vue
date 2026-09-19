<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6cqm3b0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6cqm3b0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:swimming-pool" /></template>
