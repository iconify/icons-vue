<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-1w2wbkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="y-1w2wbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:share-square" /></template>
