<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc05_6b-l.css';
import '../../css/m/mn1a8yxak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yc05_6b-l"/><path clip-rule="evenodd" class="mn1a8yxak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:picture-16" /></template>
