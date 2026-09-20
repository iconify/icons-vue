<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd-si8bfj.css';
import '../../css/z/zn8lzqb4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xd-si8bfj"/><path class="zn8lzqb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rwmarkable" /></template>
