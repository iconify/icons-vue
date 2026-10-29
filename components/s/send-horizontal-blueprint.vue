<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/m/mi93eg5bq.css';
import '../../css/y/y54jm9wsc.css';
import '../../css/v/vdwfx9spf.css';
import '../../css/s/s50qotckc.css';
import '../../css/h/h0rhmfbpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="mi93eg5bq wm-deco"/><path class="wm-deco y54jm9wsc"/><path class="vdwfx9spf wm-deco"/><path class="s50qotckc wm-k"/><path class="h0rhmfbpn wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:send-horizontal-blueprint" /></template>
