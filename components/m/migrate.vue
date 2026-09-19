<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z25feoxtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z25feoxtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:migrate" /></template>
