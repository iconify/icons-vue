<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqqdg9bxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bqqdg9bxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:mathematics-display-inline" /></template>
