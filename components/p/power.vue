<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkqwq23fc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hkqwq23fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:power" /></template>
