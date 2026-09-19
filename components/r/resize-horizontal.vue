<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6d7aiw7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i6d7aiw7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:resize-horizontal" /></template>
