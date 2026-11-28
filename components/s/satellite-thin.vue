<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz3ht99ey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="zz3ht99ey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:satellite-thin" /></template>
