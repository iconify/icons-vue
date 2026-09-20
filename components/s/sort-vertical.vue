<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arb81b3en.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="arb81b3en"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:sort-vertical" /></template>
