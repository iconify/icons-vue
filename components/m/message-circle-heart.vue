<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/v/v5fz6ctfc.css';
import '../../css/s/sdzbjqbjm.css';
import '../../css/s/sewtrvbyb.css';
import '../../css/h/hfg9ykbue.css';
import '../../css/e/eda20jzdt.css';
import '../../css/m/mibyckp-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="v5fz6ctfc wm-shadow"/><path class="sdzbjqbjm"/><path class="sewtrvbyb"/><path class="hfg9ykbue"/><path class="eda20jzdt"/><path class="mibyckp-d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-retro:message-circle-heart" /></template>
