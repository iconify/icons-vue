<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs18x8bqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs18x8bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:moon" /></template>
