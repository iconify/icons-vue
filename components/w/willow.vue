<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdfli1b4k.css';
import '../../css/j/j3rnxybvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mdfli1b4k"/><path class="j3rnxybvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:willow" /></template>
