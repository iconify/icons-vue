<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybm7tbcok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ybm7tbcok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:venmo" /></template>
