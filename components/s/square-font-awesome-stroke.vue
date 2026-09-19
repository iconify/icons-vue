<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6vt8fbcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="e6vt8fbcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:square-font-awesome-stroke" /></template>
