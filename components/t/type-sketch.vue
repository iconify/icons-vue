<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/g5ps4wb3c.css';
import '../../css/v/vrn_zwi2z.css';
import '../../css/w/w574b0b2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="g5ps4wb3c wm-k"/><path class="vrn_zwi2z wm-k"/><path class="w574b0b2r wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:type-sketch" /></template>
