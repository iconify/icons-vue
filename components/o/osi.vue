<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7v4vubya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="m7v4vubya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:osi" /></template>
