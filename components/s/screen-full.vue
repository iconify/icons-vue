<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkir8nb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jkir8nb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:screen-full" /></template>
