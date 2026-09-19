<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs9-6d97q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1664};
const content = `<path class="vs9-6d97q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:user-secret" /></template>
