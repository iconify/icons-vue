<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/r76qbi3sf.css';
import '../../css/m/mfyqqqb4c.css';
import '../../css/n/n_30woblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="r76qbi3sf"/><path class="mfyqqqb4c wm-k"/><path class="n_30woblz wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tag-sketch" /></template>
