<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt_9d4b_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="lt_9d4b_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:road" /></template>
