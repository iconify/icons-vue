<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrvyyj78y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="yrvyyj78y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:ultralytics-hub" /></template>
