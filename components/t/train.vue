<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2-lge2lf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="b2-lge2lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:train" /></template>
