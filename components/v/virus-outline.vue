<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxe5oobko.css';
import '../../css/w/wz_eimbrd.css';
import '../../css/h/h1vbpgb6s.css';
import '../../css/y/ywjd16bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mxe5oobko"/><path clip-rule="evenodd" class="wz_eimbrd"/><path class="h1vbpgb6s"/><path clip-rule="evenodd" class="ywjd16bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:virus-outline" /></template>
