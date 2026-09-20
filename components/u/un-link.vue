<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5t9vt_or.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n5t9vt_or"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:un-link" /></template>
