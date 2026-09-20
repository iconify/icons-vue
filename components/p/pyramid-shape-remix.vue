<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt7qfob9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wt7qfob9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:pyramid-shape-remix" /></template>
