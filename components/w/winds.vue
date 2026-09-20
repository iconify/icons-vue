<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/k/kfypxpbnr.css';
import '../../css/s/smmdwpb4s.css';
import '../../css/x/xstb4kblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kfypxpbnr"/><path class="smmdwpb4s"/><path class="xstb4kblq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:winds" /></template>
