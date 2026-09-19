<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7ts5db7w.css';
import '../../css/g/gu3211y0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="w7ts5db7w"/><path class="gu3211y0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:map-share" /></template>
