<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh1xajjpe.css';
import '../../css/f/fp7izb86i.css';
import '../../css/g/gak95vsdd.css';
import '../../css/i/inbth-b4o.css';
import '../../css/p/pgy9j8bvx.css';
import '../../css/a/aft9_vsai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dh1xajjpe"/><path class="fp7izb86i"/><path class="gak95vsdd"/><path class="inbth-b4o"/><path class="pgy9j8bvx"/><path class="aft9_vsai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:poodle" /></template>
