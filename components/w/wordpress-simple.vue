<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x69ryo0tm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x69ryo0tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:wordpress-simple" /></template>
