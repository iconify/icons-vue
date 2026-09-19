<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuzlowbon.css';
import '../../css/m/mrseh9rmw.css';
import '../../css/o/o0lf53bjy.css';
import '../../css/o/o80fjacmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fuzlowbon"/><path class="mrseh9rmw"/><path class="o0lf53bjy"/><path class="o80fjacmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:tangerine" /></template>
