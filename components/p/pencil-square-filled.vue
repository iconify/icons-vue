<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-v40p95y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-v40p95y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pencil-square-filled" /></template>
