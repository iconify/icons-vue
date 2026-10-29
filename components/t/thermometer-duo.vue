<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/s93rdabbe.css';
import '../../css/c/c4_wodreq.css';
import '../../css/w/wcute_4vd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="s93rdabbe"/><path class="c4_wodreq wm-a"/><path class="wcute_4vd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:thermometer-duo" /></template>
