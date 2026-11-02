<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4qcw2v3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4qcw2v3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:numbers-90-sort-ascending-line" /></template>
