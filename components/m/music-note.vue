<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/s/sivfj3bof.css';
import '../../css/r/rb5emwb6v.css';
import '../../css/g/gle5llb7u.css';
import '../../css/r/rh9qoibkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="sivfj3bof"/><path class="rb5emwb6v wm-shine"/><path class="gle5llb7u"/><path class="rh9qoibkn wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:music-note" /></template>
