<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2omfxbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="f2omfxbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:volume-high" /></template>
