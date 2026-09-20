<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/r31eezbqv.css';
import '../../css/u/u00ey8bps.css';
import '../../css/y/ynz9_ybsk.css';
import '../../css/j/jpdqneb7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="r31eezbqv"/><circle class="u00ey8bps"/><path class="ynz9_ybsk"/><path class="jpdqneb7h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:notification-unread-lines-linear" /></template>
