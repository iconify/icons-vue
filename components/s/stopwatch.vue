<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6npdccvb.css';
import '../../css/f/f7yrgob5n.css';
import '../../css/r/rkd56vgis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6npdccvb"/><path class="f7yrgob5n"/><path clip-rule="evenodd" class="rkd56vgis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:stopwatch" /></template>
