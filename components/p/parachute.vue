<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyiav2-py.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="xyiav2-py"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:parachute" /></template>
