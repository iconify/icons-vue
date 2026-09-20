<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtdofk4_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gtdofk4_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:tree-3-remix" /></template>
