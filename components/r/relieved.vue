<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7269db2g.css';
import '../../css/l/lmrf6zs5l.css';
import '../../css/b/bs0zlccnk.css';
import '../../css/q/q7i633bxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i7269db2g"/><path class="lmrf6zs5l"/><path class="bs0zlccnk"/><path class="q7i633bxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:relieved" /></template>
