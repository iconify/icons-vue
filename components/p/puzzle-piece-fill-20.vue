<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e00ealyrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e00ealyrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:puzzle-piece-fill-20" /></template>
