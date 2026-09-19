<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8-oes8zd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="c8-oes8zd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:stop" /></template>
