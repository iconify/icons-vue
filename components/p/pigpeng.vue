<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5cg5srht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="j5cg5srht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pigpeng" /></template>
