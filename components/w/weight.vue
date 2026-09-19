<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je0dw8bgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="je0dw8bgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:weight" /></template>
