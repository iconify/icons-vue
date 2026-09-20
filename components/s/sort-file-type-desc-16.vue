<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6g6x7bsy.css';
import '../../css/v/vzru2hbyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c6g6x7bsy"/><path clip-rule="evenodd" class="vzru2hbyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:sort-file-type-desc-16" /></template>
