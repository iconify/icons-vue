<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc14oeb9i.css';
import '../../css/m/mpw226b7d.css';
import '../../css/d/dfju2ib8j.css';
import '../../css/v/v79z25b5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gc14oeb9i"/><path class="mpw226b7d"/><path class="dfju2ib8j"/><path class="v79z25b5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:station" /></template>
