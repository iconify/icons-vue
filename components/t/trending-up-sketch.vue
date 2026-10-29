<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/ojpnoebxg.css';
import '../../css/z/z686sq8ka.css';
import '../../css/s/s9xijib5f.css';
import '../../css/f/fx3xvojda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ojpnoebxg wm-k"/><path class="wm-a z686sq8ka"/><path class="s9xijib5f wm-k"/><path class="fx3xvojda wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:trending-up-sketch" /></template>
