<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd4v7obem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hd4v7obem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:shopping-bag-with-music-notes-eighth" /></template>
