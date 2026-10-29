<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/t_zmzab8k.css';
import '../../css/b/b6_46kbps.css';
import '../../css/f/fx7n841gh.css';
import '../../css/x/x2ymrx5ul.css';
import '../../css/o/ow20b-m-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="t_zmzab8k"/><path class="b6_46kbps wm-k"/><path class="fx7n841gh wm-a"/><path class="wm-k x2ymrx5ul"/><path class="ow20b-m-k wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pizza-sketch" /></template>
