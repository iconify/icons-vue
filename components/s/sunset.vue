<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_bxzvurr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="o_bxzvurr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:sunset" /></template>
