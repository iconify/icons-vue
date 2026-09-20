<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d46-0giua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d46-0giua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:share" /></template>
