<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_xu1cb5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="h_xu1cb5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:squarerecord" /></template>
