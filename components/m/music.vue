<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdodvvbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":560,"height":830};
const content = `<path class="vdodvvbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:music" /></template>
