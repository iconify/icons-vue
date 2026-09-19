<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj8efxbhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wj8efxbhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:view-grid-add" /></template>
