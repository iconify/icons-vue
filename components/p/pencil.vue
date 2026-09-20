<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxql92bcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xxql92bcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:pencil" /></template>
