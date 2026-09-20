<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qosvqvk2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qosvqvk2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-circle" /></template>
