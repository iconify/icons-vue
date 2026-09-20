<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x16sxhudz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x16sxhudz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:square-dashed" /></template>
