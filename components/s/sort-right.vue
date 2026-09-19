<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyjt9lq7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wyjt9lq7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:sort-right" /></template>
