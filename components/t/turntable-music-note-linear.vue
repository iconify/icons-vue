<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qchw1hbjq.css';
import '../../css/h/hl5jo5b4t.css';
import '../../css/b/b-v3dtbhs.css';
import '../../css/f/fc4f7w-7u.css';
import '../../css/p/pwo3r4bdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qchw1hbjq"/><path class="hl5jo5b4t"/><circle class="b-v3dtbhs"/><path class="fc4f7w-7u"/><path class="pwo3r4bdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:turntable-music-note-linear" /></template>
