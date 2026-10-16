<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtxjgl01m.css';
import '../../css/z/zy3xx9cdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rtxjgl01m"/><path class="zy3xx9cdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:water-butt-20" /></template>
