<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo09mkblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo09mkblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:row-resize-filled" /></template>
