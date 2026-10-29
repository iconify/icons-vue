<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/eh0001y2z.css';
import '../../css/g/gdii7cb0u.css';
import '../../css/v/v-6eycb-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="eh0001y2z"/><path class="gdii7cb0u wm-shadow"/><path class="v-6eycb-t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:parentheses-engrave" /></template>
