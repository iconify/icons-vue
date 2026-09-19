<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja1pydb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ja1pydb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:type-h6" /></template>
