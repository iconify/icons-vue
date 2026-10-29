<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sqsx9ox8k.css';
import '../../css/p/p3xx_sbre.css';
import '../../css/y/yk-er9b1u.css';
import '../../css/w/wgep9sb5p.css';
import '../../css/z/zbwddqbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sqsx9ox8k"/><path class="p3xx_sbre wm-k"/><path class="wm-a yk-er9b1u"/><path class="wgep9sb5p wm-k"/><path class="wm-a zbwddqbyl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:milk-sketch" /></template>
