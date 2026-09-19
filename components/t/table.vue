<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/m7se3rbus.css';
import '../../css/u/upnls3bjj.css';
import '../../css/w/wg78zkb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="m7se3rbus"/><path class="upnls3bjj"/><path class="wg78zkb7p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:table" /></template>
