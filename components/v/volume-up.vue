<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap5zc5b2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ap5zc5b2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:volume-up" /></template>
