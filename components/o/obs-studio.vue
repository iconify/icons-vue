<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvj9sbfxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="pvj9sbfxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:obs-studio" /></template>
