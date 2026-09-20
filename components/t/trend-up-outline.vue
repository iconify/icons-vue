<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/getz5jb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="getz5jb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:trend-up-outline" /></template>
