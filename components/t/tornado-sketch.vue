<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/x8dkkqbfb.css';
import '../../css/e/emsx96-no.css';
import '../../css/o/oc1n9gx5w.css';
import '../../css/t/ti54u2g4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k x8dkkqbfb"/><path class="emsx96-no wm-a"/><path class="oc1n9gx5w wm-k"/><path class="ti54u2g4v wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tornado-sketch" /></template>
