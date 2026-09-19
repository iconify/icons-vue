<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0h1ucbrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="f0h1ucbrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:space-awesome" /></template>
