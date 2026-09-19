<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki7z1mb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ki7z1mb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:shield" /></template>
