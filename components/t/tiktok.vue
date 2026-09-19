<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t49-fcc2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="t49-fcc2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:tiktok" /></template>
