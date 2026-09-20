<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qiy6cs5ry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qiy6cs5ry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:squat-rock-with-inscription" /></template>
