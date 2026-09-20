<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl-a6dbis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="yl-a6dbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:text-box-1-remix" /></template>
