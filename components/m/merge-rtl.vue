<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1nv75n_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l1nv75n_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:merge-rtl" /></template>
