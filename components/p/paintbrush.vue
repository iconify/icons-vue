<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy4pt5qrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":32};
const content = `<path class="zy4pt5qrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:paintbrush" /></template>
