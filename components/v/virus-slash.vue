<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqz26c-5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="iqz26c-5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:virus-slash" /></template>
