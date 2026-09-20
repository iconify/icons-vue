<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6215pfzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c6215pfzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:milk-carton-and-cheese" /></template>
