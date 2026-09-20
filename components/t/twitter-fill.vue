<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhyd0pb-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="zhyd0pb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:twitter-fill" /></template>
