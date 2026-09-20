<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-2m00b1v.css';
import '../../css/a/a9p3m-d8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u-2m00b1v"/><path clip-rule="evenodd" class="a9p3m-d8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:page-landscape-16" /></template>
