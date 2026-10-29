<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/aj7nb3b0g.css';
import '../../css/r/rqpznn91v.css';
import '../../css/d/dyo5hzbdy.css';
import '../../css/g/g7td--57i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="aj7nb3b0g wm-k"/><path class="rqpznn91v wm-a"/><path class="dyo5hzbdy wm-k"/><path class="g7td--57i wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:person-running-sketch" /></template>
