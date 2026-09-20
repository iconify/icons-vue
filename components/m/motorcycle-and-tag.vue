<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og-moc5vi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="og-moc5vi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:motorcycle-and-tag" /></template>
