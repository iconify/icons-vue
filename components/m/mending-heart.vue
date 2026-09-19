<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lwg0v_ffw.css';
import '../../css/v/vw4s4d69i.css';
import '../../css/v/vp-phbc-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="lwg0v_ffw"/><path class="vw4s4d69i"/><path class="vp-phbc-d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:mending-heart" /></template>
