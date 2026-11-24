<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq_yc_azc.css';
import '../../css/r/rq0x_wbbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cq_yc_azc"/><path class="rq0x_wbbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:metronome-filled" /></template>
