<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuui8ccfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tuui8ccfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:search-regular-expression" /></template>
