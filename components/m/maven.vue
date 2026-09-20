<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpq-rwbig.css';
import '../../css/y/yac5kp3-q.css';
import '../../css/a/ath0yjbrq.css';
import '../../css/g/g8g9_37cy.css';
import '../../css/e/ed30wonmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><linearGradient id="SVGWeA2nrAT" x1=".125" x2="0" y1="1" y2="0"><stop offset="0%" class="wpq-rwbig"/><stop offset="37.5%" class="wpq-rwbig"/><stop offset="37.501%" class="yac5kp3-q"/><stop offset="54.25%" class="yac5kp3-q"/><stop offset="54.251%" class="ath0yjbrq"/><stop offset="69.75%" class="ath0yjbrq"/><stop offset="69.751%" class="g8g9_37cy"/><stop offset="100%" class="g8g9_37cy"/></linearGradient></defs><path fill="url(#SVGWeA2nrAT)" class="ed30wonmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:maven" /></template>
