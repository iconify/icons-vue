<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wuzd39s8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="wuzd39s8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:viadeo-square" /></template>
