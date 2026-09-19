<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuc792mew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uuc792mew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:plugins-checked" /></template>
