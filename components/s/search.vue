<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jozn2iebr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":740,"height":840};
const content = `<path class="jozn2iebr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:search" /></template>
