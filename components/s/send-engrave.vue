<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/df0z6_b6i.css';
import '../../css/j/jpd9a-q0q.css';
import '../../css/g/ga5w9h8zd.css';
import '../../css/v/v3eqelbpl.css';
import '../../css/b/btb9bc3qj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="df0z6_b6i wm-k"/><path class="jpd9a-q0q wm-a"/><path class="ga5w9h8zd wm-shadow"/><path class="v3eqelbpl wm-k"/><path class="btb9bc3qj wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:send-engrave" /></template>
