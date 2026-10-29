<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jwebfwysk.css';
import '../../css/a/a51zlh9nm.css';
import '../../css/b/bbm6b67wr.css';
import '../../css/i/ih9g-eb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jwebfwysk wm-k"/><path class="a51zlh9nm wm-a"/><path class="bbm6b67wr wm-k"/><path class="ih9g-eb6y wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sprout-sketch" /></template>
