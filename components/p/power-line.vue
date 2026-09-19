<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crgdrwxoi.css';
import '../../css/o/o1lu20b4y.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 crgdrwxoi"/><path class="clr-i-outline clr-i-outline-path-2 o1lu20b4y"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:power-line" /></template>
