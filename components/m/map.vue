<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuukbzbho.css';
import '../../css/x/xw75jrbbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="vuukbzbho"/><path class="xw75jrbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:map" /></template>
