<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxgbzuu-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxgbzuu-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tree-pine-filled" /></template>
