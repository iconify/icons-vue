<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/j/jd59erb6t.css';
import '../../css/a/a3k-1f3du.css';
import '../../css/x/xv2fgjbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="jd59erb6t wm-deco"/><path class="a3k-1f3du wm-deco"/><path class="xv2fgjbuo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pause-blueprint" /></template>
