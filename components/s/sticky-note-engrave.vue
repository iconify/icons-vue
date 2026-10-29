<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pkw_vuvwi.css';
import '../../css/t/t09_pz2-q.css';
import '../../css/m/mgjs6b63c.css';
import '../../css/c/c4_v7i59t.css';
import '../../css/o/o8mkkgbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pkw_vuvwi wm-k"/><path class="t09_pz2-q wm-a"/><path class="mgjs6b63c wm-shadow"/><path class="c4_v7i59t wm-k"/><path class="o8mkkgbix wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sticky-note-engrave" /></template>
