<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-zerkbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="j-zerkbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:shintoist-14" /></template>
