<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6y1d0ihj.css';
import '../../css/y/ykou9hbnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x6y1d0ihj"/><path class="ykou9hbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:test-tube-stroke-20" /></template>
