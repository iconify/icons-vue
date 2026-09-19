<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2ibnsbfx.css';
import '../../css/k/kb4_7ccic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="q2ibnsbfx"/><path class="kb4_7ccic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:swagger" /></template>
