<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae3eucc9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ae3eucc9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:plane-up" /></template>
