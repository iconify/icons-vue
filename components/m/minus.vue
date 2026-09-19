<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oasy1vb8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="oasy1vb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:minus" /></template>
