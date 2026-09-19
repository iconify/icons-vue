<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1yn-jb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="y1yn-jb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:pin-fill-12" /></template>
