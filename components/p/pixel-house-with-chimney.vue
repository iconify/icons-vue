<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzh0n7bgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vzh0n7bgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-house-with-chimney" /></template>
