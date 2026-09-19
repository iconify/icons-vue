<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2srrkj6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="m2srrkj6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:whiteboard" /></template>
