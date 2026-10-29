<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/w/w1fa89b6r.css';
import '../../css/z/zis5pgb4d.css';
import '../../css/o/o7-ag87sb.css';
import '../../css/z/zygpqzk7v.css';
import '../../css/e/ewn913uqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="w1fa89b6r wm-deco"/><path class="wm-deco zis5pgb4d"/><path class="o7-ag87sb wm-deco"/><path class="wm-k zygpqzk7v"/><path class="ewn913uqn wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pill-blueprint" /></template>
