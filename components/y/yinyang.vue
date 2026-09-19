<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysb-1jbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1025};
const content = `<path class="ysb-1jbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:yinyang" /></template>
