<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfnwxgt6p.css';
import '../../css/c/c9p0p_5vn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="wfnwxgt6p"/><path class="c9p0p_5vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:trpc" /></template>
