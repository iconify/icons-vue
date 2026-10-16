<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucyj_sb_u.css';
import '../../css/l/l0cgkbf-f.css';
import '../../css/b/bx8fgc64p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ucyj_sb_u"/><path class="l0cgkbf-f"/><path class="bx8fgc64p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tiny-house-20" /></template>
