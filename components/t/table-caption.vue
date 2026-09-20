<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvt4khnuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tvt4khnuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:table-caption" /></template>
