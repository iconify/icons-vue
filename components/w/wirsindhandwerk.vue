<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gezj21rlz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="gezj21rlz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:wirsindhandwerk" /></template>
