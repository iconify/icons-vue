<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2jihr4ce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p2jihr4ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:sbd" /></template>
