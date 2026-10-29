<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpaoo99bk.css';
import '../../css/r/rnt8kobtz.css';
import '../../css/e/ecfshgrfk.css';
import '../../css/e/e1s9j5b3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpaoo99bk wm-k"/><path class="rnt8kobtz wm-a"/><path class="ecfshgrfk wm-k"/><path class="e1s9j5b3x wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:swap" /></template>
