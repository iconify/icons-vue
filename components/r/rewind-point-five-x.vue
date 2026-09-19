<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn6i8jbmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pn6i8jbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:rewind-point-five-x" /></template>
