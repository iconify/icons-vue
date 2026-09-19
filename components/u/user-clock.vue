<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb8jpq1oe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="zb8jpq1oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:user-clock" /></template>
