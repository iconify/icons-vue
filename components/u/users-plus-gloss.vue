<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/r/roesr2bch.css';
import '../../css/w/wo0uzib6g.css';
import '../../css/s/syi3z2buw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="roesr2bch wm-k"/><path class="wm-a wo0uzib6g"/><path class="syi3z2buw wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:users-plus-gloss" /></template>
