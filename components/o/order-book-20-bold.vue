<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4m5opfgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m4m5opfgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:order-book-20-bold" /></template>
