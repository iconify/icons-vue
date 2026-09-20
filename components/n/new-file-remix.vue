<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqpg7wbgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yqpg7wbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:new-file-remix" /></template>
