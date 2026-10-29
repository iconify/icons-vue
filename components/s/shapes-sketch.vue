<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/yyaz67b1l.css';
import '../../css/h/hw_2ns8uj.css';
import '../../css/f/fejh84b-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="yyaz67b1l"/><path class="hw_2ns8uj wm-k"/><path class="fejh84b-m wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shapes-sketch" /></template>
