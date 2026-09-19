<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/i/ix74hpb0f.css';
import '../../css/d/dicptfbfk.css';
import '../../css/x/xei8vkhxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ix74hpb0f"/><path class="dicptfbfk"/><path class="xei8vkhxk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:notification-circle" /></template>
