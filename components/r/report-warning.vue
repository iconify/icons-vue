<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug6jb8s5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ug6jb8s5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:report-warning" /></template>
