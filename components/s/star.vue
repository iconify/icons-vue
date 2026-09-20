<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h50m28b6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h50m28b6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:star" /></template>
