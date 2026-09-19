<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svvim6bry.css';
import '../../css/x/x8snpsbmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="svvim6bry"/><path class="x8snpsbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:stacked-move" /></template>
