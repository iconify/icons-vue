<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h63rd_q9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="h63rd_q9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wall-with-battlement" /></template>
