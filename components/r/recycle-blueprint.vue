<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/b/bok_3xbsi.css';
import '../../css/r/r2e6-o--s.css';
import '../../css/b/buhykv-du.css';
import '../../css/z/z56dd-dvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="bok_3xbsi wm-deco"/><path class="r2e6-o--s wm-deco"/><path class="buhykv-du wm-k"/><path class="wm-a z56dd-dvf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:recycle-blueprint" /></template>
