<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yolb2c1_c.css';
import '../../css/r/rvcb4bedk.css';
import '../../css/y/y-7m_e66k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="yolb2c1_c"/><path class="rvcb4bedk"/><path class="y-7m_e66k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:retweet" /></template>
