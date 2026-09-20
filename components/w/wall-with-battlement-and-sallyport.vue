<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3h0hpbxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j3h0hpbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wall-with-battlement-and-sallyport" /></template>
