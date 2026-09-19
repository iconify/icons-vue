<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd9e0jb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":448};
const content = `<path class="yd9e0jb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:moon" /></template>
