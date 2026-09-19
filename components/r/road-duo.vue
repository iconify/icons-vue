<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zksu7dn2w.css';
import '../../css/y/yt1oy9ckg.css';
import '../../css/i/iyrbwab4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="zksu7dn2w"/><path class="yt1oy9ckg"/><path class="iyrbwab4q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:road-duo" /></template>
