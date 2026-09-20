<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-o_fbdju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m-o_fbdju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:table-add-column-before-ltr" /></template>
