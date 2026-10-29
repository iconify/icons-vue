<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/a/a6sztlqbs.css';
import '../../css/z/zkzz2bx5y.css';
import '../../css/o/o7-ag87sb.css';
import '../../css/w/w-lwaj9cw.css';
import '../../css/f/frhmwlb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="a6sztlqbs wm-deco"/><path class="wm-deco zkzz2bx5y"/><path class="o7-ag87sb wm-deco"/><path class="w-lwaj9cw wm-k"/><path class="frhmwlb7n wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mushroom-blueprint" /></template>
