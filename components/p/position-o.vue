<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v--o8dbgk.css';
import '../../css/y/yol252b6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="v--o8dbgk"/><path class="yol252b6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:position-o" /></template>
