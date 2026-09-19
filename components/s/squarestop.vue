<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2_f_obtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="d2_f_obtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:squarestop" /></template>
