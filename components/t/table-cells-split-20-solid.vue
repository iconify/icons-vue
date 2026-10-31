<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3jp-_2dc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="s3jp-_2dc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:table-cells-split-20-solid" /></template>
