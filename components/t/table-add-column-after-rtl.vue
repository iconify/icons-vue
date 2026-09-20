<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6nny44xw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s6nny44xw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:table-add-column-after-rtl" /></template>
