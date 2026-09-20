<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4d0xccxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t4d0xccxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:refresh" /></template>
