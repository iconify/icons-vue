<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/q/q_boskbot.css';
import '../../css/f/f2kuhacpl.css';
import '../../css/k/ksu4hvb6k.css';
import '../../css/n/nf7b53bmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="q_boskbot"/><path class="f2kuhacpl"/><path class="ksu4hvb6k"/><path class="nf7b53bmy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:refresh-ccw-sparkles-sharp-two-tone" /></template>
