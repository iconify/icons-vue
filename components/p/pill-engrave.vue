<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/ce6fhfb5v.css';
import '../../css/c/cstk1up5l.css';
import '../../css/c/cr6ik54-e.css';
import '../../css/t/tph8vb83n.css';
import '../../css/e/ewn913uqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ce6fhfb5v wm-k"/><path class="cstk1up5l wm-a"/><path class="cr6ik54-e wm-shadow"/><path class="tph8vb83n wm-k"/><path class="ewn913uqn wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pill-engrave" /></template>
