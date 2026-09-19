<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxsp-2zfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="bxsp-2zfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:webflow" /></template>
