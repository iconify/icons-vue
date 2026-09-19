<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6gi9gily.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="y6gi9gily"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:vector-polygon" /></template>
