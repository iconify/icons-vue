<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/teiclfxwa.css';
import '../../css/k/ki722bqyl.css';
import '../../css/o/oaan660fk.css';
import '../../css/a/a-cpzbx-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="teiclfxwa"/><path class="ki722bqyl wm-k"/><path class="oaan660fk wm-k"/><path class="a-cpzbx-q wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:percent-sketch" /></template>
