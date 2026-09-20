<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp49xnb5l.css';
import '../../css/w/wln7u9w6d.css';
import '../../css/d/d45omcbyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="hp49xnb5l"/><path class="wln7u9w6d"/><path class="d45omcbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:snapcast" /></template>
