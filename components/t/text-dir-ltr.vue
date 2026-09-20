<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_xk9kz7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e_xk9kz7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:text-dir-ltr" /></template>
