<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulipixb_y.css';
import '../../css/c/cl9z5d_3w.css';
import '../../css/h/hsahbabwh.css';
import '../../css/a/aizck2ejj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ulipixb_y"/><path class="cl9z5d_3w"/><path class="hsahbabwh"/><path class="aizck2ejj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:opencv-wordmark" /></template>
