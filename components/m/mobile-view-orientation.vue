<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkwnyu5zy.css';
import '../../css/o/onqnis1mn.css';
import '../../css/h/h6hpqtbrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hkwnyu5zy"/><path class="onqnis1mn"/><path class="h6hpqtbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:mobile-view-orientation" /></template>
