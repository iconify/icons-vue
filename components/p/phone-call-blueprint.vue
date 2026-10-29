<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/b/b5-4_mb1p.css';
import '../../css/b/b67pbnbav.css';
import '../../css/t/t86fb0sry.css';
import '../../css/i/is_-82b8q.css';
import '../../css/s/sprk3fbkq.css';
import '../../css/c/cghw12usi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="b5-4_mb1p wm-deco"/><path class="b67pbnbav wm-deco"/><path class="t86fb0sry wm-deco"/><path class="is_-82b8q wm-k"/><path class="sprk3fbkq wm-s"/><path class="cghw12usi wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:phone-call-blueprint" /></template>
