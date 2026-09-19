<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p82xhrlbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="p82xhrlbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:surprise" /></template>
