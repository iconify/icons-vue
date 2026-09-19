<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8aw46iem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="c8aw46iem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:plus-circle" /></template>
