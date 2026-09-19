<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad80vl__v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ad80vl__v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:wine-glass-alt" /></template>
