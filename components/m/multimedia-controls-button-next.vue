<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz45orb-l.css';
import '../../css/p/pd3uy56kd.css';
import '../../css/y/yhzwzc4av.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wz45orb-l"/><path class="pd3uy56kd"/><path class="yhzwzc4av"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:multimedia-controls-button-next" /></template>
