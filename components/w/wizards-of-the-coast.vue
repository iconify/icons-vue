<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svzk-5qxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="svzk-5qxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:wizards-of-the-coast" /></template>
