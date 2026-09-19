<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihb_q5xeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ihb_q5xeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:share-stroke-16" /></template>
