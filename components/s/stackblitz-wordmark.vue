<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysufu1sye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ysufu1sye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:stackblitz-wordmark" /></template>
