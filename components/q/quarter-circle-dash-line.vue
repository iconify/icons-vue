<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln7uv3d2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ln7uv3d2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:quarter-circle-dash-line" /></template>
