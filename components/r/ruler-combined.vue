<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0zyy8ctg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z0zyy8ctg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:ruler-combined" /></template>
