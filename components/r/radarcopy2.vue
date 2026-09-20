<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9y04fb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f9y04fb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:radarcopy2" /></template>
