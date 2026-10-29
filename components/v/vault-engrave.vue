<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nk8myvbrt.css';
import '../../css/e/e607we0qg.css';
import '../../css/y/yj_y3dp7d.css';
import '../../css/f/f48qsgb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nk8myvbrt wm-k"/><path class="e607we0qg wm-shadow"/><path class="wm-k yj_y3dp7d"/><path class="f48qsgb5t wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:vault-engrave" /></template>
