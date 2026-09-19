<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikd4kd-ww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ikd4kd-ww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:snowplow" /></template>
