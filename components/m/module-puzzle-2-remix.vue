<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b10v80bpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b10v80bpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:module-puzzle-2-remix" /></template>
