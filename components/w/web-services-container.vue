<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsrzeq-ig.css';
import '../../css/t/tz_5mvbtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hsrzeq-ig"/><path class="tz_5mvbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:web-services-container" /></template>
