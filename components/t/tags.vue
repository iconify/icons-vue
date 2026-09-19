<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umeg4vy6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="umeg4vy6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:tags" /></template>
