<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn9m6vbtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vn9m6vbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:phone" /></template>
