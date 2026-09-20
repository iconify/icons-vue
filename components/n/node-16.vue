<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6lrr_beh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s6lrr_beh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:node-16" /></template>
