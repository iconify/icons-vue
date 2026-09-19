<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-ep33b6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="r-ep33b6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:timeline-progress" /></template>
