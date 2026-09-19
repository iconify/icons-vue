<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6lft_bql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="x6lft_bql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:select" /></template>
