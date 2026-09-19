<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyad3pbvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wyad3pbvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:splotch" /></template>
