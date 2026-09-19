<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e75f81i5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":479,"height":512};
const content = `<path class="e75f81i5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:progress" /></template>
