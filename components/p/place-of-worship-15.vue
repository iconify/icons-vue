<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfefpob_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qfefpob_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:place-of-worship-15" /></template>
