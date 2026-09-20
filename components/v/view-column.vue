<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7zll976v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w7zll976v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:view-column" /></template>
