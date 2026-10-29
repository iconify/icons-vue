<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/w/wluwfzejn.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/l/lqm3yub_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wluwfzejn wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="lqm3yub_u wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:stop-blueprint" /></template>
