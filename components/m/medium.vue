<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xusj4ss4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="xusj4ss4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:medium" /></template>
