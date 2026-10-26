<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4977lbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":240,"height":96};
const content = `<path class="i4977lbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:n8n" /></template>
