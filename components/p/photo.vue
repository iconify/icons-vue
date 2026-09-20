<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy9jgkulp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jy9jgkulp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:photo" /></template>
