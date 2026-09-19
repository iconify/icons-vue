<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvg2_zb3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="rvg2_zb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:zhihu" /></template>
