<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzc8m079p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="hzc8m079p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:maximize-fill-12" /></template>
