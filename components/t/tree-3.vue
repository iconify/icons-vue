<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzvq67bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzvq67bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:tree-3" /></template>
