<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd13973hj.css';
import '../../css/g/gu_5xob7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd13973hj"/><path class="gu_5xob7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:wifi-signal-4-bold" /></template>
