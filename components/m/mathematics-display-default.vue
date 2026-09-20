<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lczo6ys_s.css';
import '../../css/c/cxrrxpb0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lczo6ys_s"/><path class="cxrrxpb0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:mathematics-display-default" /></template>
