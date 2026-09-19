<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvnmyxb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yvnmyxb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:trophy" /></template>
