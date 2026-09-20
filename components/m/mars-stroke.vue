<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jadz-ybzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jadz-ybzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:mars-stroke" /></template>
