<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn6fo7tny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="qn6fo7tny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:thermometer" /></template>
