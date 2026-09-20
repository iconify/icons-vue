<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzqfh5bfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzqfh5bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:wifi-off-line" /></template>
