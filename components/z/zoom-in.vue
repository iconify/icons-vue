<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thr4qybcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="thr4qybcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:zoom-in" /></template>
