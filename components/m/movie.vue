<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txxwnozyd.css';
import '../../css/j/j5s8mp-8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="txxwnozyd"/><path class="j5s8mp-8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:movie" /></template>
