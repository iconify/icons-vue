<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg419tbbu.css';
import '../../css/k/koi2gi6-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wg419tbbu"/><path class="koi2gi6-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:text-input" /></template>
