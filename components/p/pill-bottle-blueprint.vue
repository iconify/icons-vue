<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/p/pm89hh4er.css';
import '../../css/f/f22o3bcfn.css';
import '../../css/j/jgka1gbzk.css';
import '../../css/v/vhcfjabbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="pm89hh4er wm-deco"/><path class="f22o3bcfn wm-deco"/><path class="jgka1gbzk wm-k"/><path class="vhcfjabbb wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pill-bottle-blueprint" /></template>
