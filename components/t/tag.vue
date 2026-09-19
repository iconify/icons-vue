<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5ix4pw3w.css';
import '../../css/y/yx_v63b6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q5ix4pw3w"/><path class="yx_v63b6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:tag" /></template>
