<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iandkib0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iandkib0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:wrench-remix" /></template>
