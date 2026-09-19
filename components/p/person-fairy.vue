<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hxx5cbc5a.css';
import '../../css/t/tof8bjbhp.css';
import '../../css/v/vm8glirhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="hxx5cbc5a"/><path class="tof8bjbhp"/><path class="vm8glirhj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:person-fairy" /></template>
