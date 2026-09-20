<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugyn5xbme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ugyn5xbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:webcam" /></template>
