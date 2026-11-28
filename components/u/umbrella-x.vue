<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3fzftb9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3fzftb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:umbrella-x" /></template>
