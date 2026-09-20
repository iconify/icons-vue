<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa55b9btm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xa55b9btm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:stop-16" /></template>
