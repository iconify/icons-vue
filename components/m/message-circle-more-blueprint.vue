<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/r/rf4w12c9e.css';
import '../../css/r/r5fftoboz.css';
import '../../css/v/v0ntukbdq.css';
import '../../css/y/y49trb-sx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="rf4w12c9e wm-deco"/><path class="r5fftoboz wm-deco"/><path class="v0ntukbdq wm-k"/><path class="wm-a y49trb-sx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-circle-more-blueprint" /></template>
