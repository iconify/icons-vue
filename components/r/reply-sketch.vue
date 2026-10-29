<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/u_sbmst1y.css';
import '../../css/e/el_7qjb5j.css';
import '../../css/t/twn9oxeew.css';
import '../../css/m/mqak27l0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="u_sbmst1y wm-k"/><path class="el_7qjb5j wm-a"/><path class="twn9oxeew wm-k"/><path class="mqak27l0q wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:reply-sketch" /></template>
