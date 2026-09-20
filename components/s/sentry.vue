<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q26_qtrtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":227};
const content = `<path class="q26_qtrtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sentry" /></template>
