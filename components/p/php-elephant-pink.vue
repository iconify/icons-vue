<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1ccb2w-q.css';
import '../../css/t/toaf3ebik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o1ccb2w-q"/><path class="toaf3ebik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:php-elephant-pink" /></template>
