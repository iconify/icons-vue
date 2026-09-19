<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsqv74bmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fsqv74bmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:window-minimize" /></template>
