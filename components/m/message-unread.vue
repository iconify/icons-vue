<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c_4rwbbkx.css';
import '../../css/i/iq4t2p2xt.css';
import '../../css/f/fulwhhb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="c_4rwbbkx"/><path class="iq4t2p2xt"/><circle class="fulwhhb_m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:message-unread" /></template>
