<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k3_8jwp2c.css';
import '../../css/a/acs8qldpc.css';
import '../../css/b/b29-gmble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="k3_8jwp2c"/><path class="acs8qldpc"/><path class="b29-gmble"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:playback-speed" /></template>
