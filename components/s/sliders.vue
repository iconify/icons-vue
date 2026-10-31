<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/i/icg4znpvz.css';
import '../../css/c/c93kobbbl.css';
import '../../css/b/btx7f2bco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="icg4znpvz wm-k"/><path class="c93kobbbl wm-a"/><path class="btx7f2bco wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:sliders" /></template>
