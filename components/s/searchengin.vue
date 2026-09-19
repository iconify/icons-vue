<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5612ukdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="x5612ukdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:searchengin" /></template>
