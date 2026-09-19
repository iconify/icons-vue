<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s2x0lbi2z.css';
import '../../css/y/ypz3se3da.css';
import '../../css/v/vzxgn5s_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="s2x0lbi2z"/><path class="ypz3se3da"/><path class="vzxgn5s_f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:window" /></template>
