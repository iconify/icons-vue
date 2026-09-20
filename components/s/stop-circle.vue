<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6100mb-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t6100mb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:stop-circle" /></template>
