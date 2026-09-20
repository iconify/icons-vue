<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3d7bpber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l3d7bpber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:table-move-column-before-rtl" /></template>
