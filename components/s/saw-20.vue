<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov7zehb3m.css';
import '../../css/r/rs63jfdfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ov7zehb3m"/><path class="rs63jfdfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:saw-20" /></template>
