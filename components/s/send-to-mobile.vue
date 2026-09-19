<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/e/e6ubjbbgg.css';
import '../../css/a/aznwbrbwl.css';
import '../../css/f/fco_zwbfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e6ubjbbgg"/><path class="aznwbrbwl"/><path class="fco_zwbfx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:send-to-mobile" /></template>
