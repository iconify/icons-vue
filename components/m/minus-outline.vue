<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au9hlnb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="au9hlnb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:minus-outline" /></template>
