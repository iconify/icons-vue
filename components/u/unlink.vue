<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/e/e1wyg2csk.css';
import '../../css/y/yo27kfb1y.css';
import '../../css/d/dbcx10b6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="wwvp95byt"><path class="e1wyg2csk"/><path class="yo27kfb1y"/><path class="dbcx10b6c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:unlink" /></template>
