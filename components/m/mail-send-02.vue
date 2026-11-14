<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/s22kwguip.css';
import '../../css/d/df-j23bjo.css';
import '../../css/a/airf7lg3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="s22kwguip"/><path class="df-j23bjo"/><path class="airf7lg3z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mail-send-02" /></template>
