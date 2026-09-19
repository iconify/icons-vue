<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c79n5y3hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="c79n5y3hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:plane" /></template>
