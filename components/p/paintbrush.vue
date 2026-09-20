<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzz6dhkzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzz6dhkzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:paintbrush" /></template>
