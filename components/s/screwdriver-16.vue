<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/veidlab1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="veidlab1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:screwdriver-16" /></template>
