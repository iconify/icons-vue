<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvxhxcb1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pvxhxcb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:text-flow-rtl" /></template>
