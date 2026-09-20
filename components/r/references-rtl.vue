<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuafxuqhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nuafxuqhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:references-rtl" /></template>
