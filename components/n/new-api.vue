<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/p/pr4f-9s_n.css';
import '../../css/r/ra5ekzk-k.css';
import '../../css/d/dkikyne8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="pr4f-9s_n"/><path class="ra5ekzk-k"/><path class="dkikyne8i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:new-api" /></template>
