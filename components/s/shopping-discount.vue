<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_y1646an.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f_y1646an"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:shopping-discount" /></template>
