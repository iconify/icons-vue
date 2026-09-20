<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk-x0v-3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wk-x0v-3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:ticket" /></template>
