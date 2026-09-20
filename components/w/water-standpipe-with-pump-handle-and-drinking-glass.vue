<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb0hgobzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hb0hgobzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:water-standpipe-with-pump-handle-and-drinking-glass" /></template>
