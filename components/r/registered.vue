<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3cgxdb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="m3cgxdb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:registered" /></template>
