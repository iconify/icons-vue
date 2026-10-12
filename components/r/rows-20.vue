<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdq19-but.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jdq19-but"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rows-20" /></template>
