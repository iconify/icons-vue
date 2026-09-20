<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld_f683ql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ld_f683ql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:table-move-column-after-rtl" /></template>
