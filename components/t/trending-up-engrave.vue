<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pft8d2bkv.css';
import '../../css/w/we6wbhteb.css';
import '../../css/f/fk6vrq42t.css';
import '../../css/g/gm6dav2hm.css';
import '../../css/a/ax2ntcc7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pft8d2bkv wm-k"/><path class="we6wbhteb wm-a"/><path class="fk6vrq42t wm-shadow"/><path class="gm6dav2hm wm-k"/><path class="ax2ntcc7z wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:trending-up-engrave" /></template>
