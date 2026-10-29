<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjgn7172q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjgn7172q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:notebook-solid" /></template>
