<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/ih6qqcvxi.css';
import '../../css/c/ckiijib5f.css';
import '../../css/c/ct7tzk2gs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ih6qqcvxi"/><path class="ckiijib5f"/><path class="ct7tzk2gs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:trophy-sketch" /></template>
