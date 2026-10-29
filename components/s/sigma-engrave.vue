<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nbtn6r3qe.css';
import '../../css/z/z7rsvjb5o.css';
import '../../css/o/o1fxrtmvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nbtn6r3qe"/><path class="wm-shadow z7rsvjb5o"/><path class="o1fxrtmvk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sigma-engrave" /></template>
