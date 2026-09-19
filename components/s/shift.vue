<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtyx4x3lv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qtyx4x3lv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:shift" /></template>
