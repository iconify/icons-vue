<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyg283b4l.css';
import '../../css/h/hish2dbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dyg283b4l"/><path class="hish2dbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:sparkle-filled" /></template>
